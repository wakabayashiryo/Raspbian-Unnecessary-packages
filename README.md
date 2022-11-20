### 必要なパッケージに合わせてOSを選択すると良い
パッケージリスト一覧表示
- ## あまり必要としないパッケージ(Raspberry Pi OS Bullseye with desktop)
    - パッケージ一覧
        - geany
        - libraspberrypi-doc
        - vlc
        - galculator
        - sense-hat
        - Thonny python IDE
    - 消去コマンド  
        > sudo apt -y purge geany geany-common vlc* libraspberrypi-docgpicview galculator sense-hat 
	
        > sudo apt -y autoremove   
        > sudo apt clean

- ## あまり必要としないパッケージ(Lite)
    - 必要最小限のパッケージしか無いため、ほとんど消去するパッケージはない
