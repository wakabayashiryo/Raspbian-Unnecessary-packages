- ## [NOOBSって何！？Raspbianの違いとは？](https://vasco-blog.com/blog/2019/07/06/deference-noobs-and-raspbian/)
### 必要なパッケージに合わせてOSを選択すると良い
パッケージリスト一覧表示
> sudo dpkg -l
- ## あまり必要としないパッケージ(NOOBS)
    - パッケージ一覧
        - wolfram-engine  
        - gnome-www-browser   
        - sonic-pi   
        - libreoffice  
        - scratch  
        - scratch2  
        - nuscratch  
        - gonme-user-guide  
        - libraspberrypi-doc  
        - pypy  
        - greenfoot  
        - python-pygame   
        - bluej   
        - nodered    
        - smart-sim   
        - VLC メディアプレイヤー
        - minecraft
        - Geany
        - claws-mail
        - gpicview
        - galculator
        - qpdfviwer
        - sense-hat
        - sense-emu-tools	
        - omxplayer
        - その他デスクトップで不要と思うパッケージ
		
	- 消去コマンド
		>sudo apt -y purge wolfram-engine gnome-www-browser sonic-pi scratch scratch2 nuscratch gnome-user-guide libraspberrypi-doc pypy greenfoot python-games bluej nodered smartsim vlc* minecraft-pi geany claws-mail gpicview galculator qpdfview sense-emu-tools sense-hat omxplayer   
		
		> sudo apt -y remove --purge libreoffice*    

		> rm -rf /home/pi/python_games/    
		> sudo rmdir /usr/local/games/   
		> sudo rmdir /usr/games/   
		> sudo rm -R ~/MagPi
		
		> sudo apt -y autoremove    
		> sudo apt clean    

- ## あまり必要としないパッケージ(Raspbian bluster with desktop)
    - パッケージ一覧
        - geany
        - libraspberrypi-doc
        - pypy
        - python-pygame
        - vlc
        - gpicview
        - galculator
        - sense-hat
        - omxplayer
        - Thonny python IDE
    - 消去コマンド  
        > sudo apt -y purge geany libraspberrypi-doc pypy python-pygame vlc gpicview galculator sense-hat omxplayer qpdfview thonny

        > sudo rmdir /usr/local/games/   
        > sudo rmdir /usr/games/   
        > sudo rm -R ~/MagPi   

        > sudo apt -y autoremove   
        > sudo apt clean

- ## あまり必要としないパッケージ(Lite)
    - 必要最小限のパッケージしか無いため、ほとんど消去するパッケージはない
