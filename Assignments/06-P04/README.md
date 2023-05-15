**Welcome to Metal Slug - Adventure - Collaborative Level Game**

**Overview:**

Metal Slug is a side-scrolling, collaborative level game developed. The game follows a group of soldiers as they battle their way through various levels filled with enemy soldiers, tanks, and other obstacles. Players have access to an array of weapons and power-ups that allow them to fight their way through the different challenges. The game can be played solo or cooperatively with up to three other players.

As players progress through the game, they collect power-ups and other items that enhance their abilities and help them defeat tougher enemies. The game features multiple difficulty levels, providing a challenge for players of all skill levels.

In Our multiplayer version, we used to RabbitMQ for message passing. We aplogize for the low fps which leads to poor quality of multiplayer gameplay.

**Credits:**
The sprite resource:
https://www.spriters-resource.com/neo_geo_ngcd/ms3
Tiled:
https://thorbjorn.itch.io/tiled

**Developers:**
1. Md Abubakkar
2. Nitish Kumar
3. Loic Konan

RabbitMQ server was provided by Dr. Terry Griffin


**USAGE:**

-> There are two ways to download project:

    • Clone the repository using below URL and navigate to Metal Slug folder in 06 – P04 folder

	URL: https://github.com/nitishkumar2306/5443-2D-NitishKumar.git

    • Download the Zip file
    
 -> Now, download PyCharm Community Edition from https://www.jetbrains.com/pycharm/download/other.html
 
 -> Load our files in PyCharm CE
 
 -> Open a terminal and write *python3 main.py queue=game-01 player=player-01*
 (write *python main.py queue=game-01 player=player-01* if you are using windows)
 
 

**Prerequisites:**
Install following dependencies using command line. Install them in the following formate pip install <dependency name>
	
Ex: pip install pytmx
	
    • pytmx
    • pygame
    • json
    • rich
    • sys
    • time
    • pika
    • random


       
		



