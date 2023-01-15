# RPG
First year project student, a classical RPG made with the C-SFML library.

## Features

* In-game save system  
* Turn-based combat with enemy AI  
* Movement management on a map  
* Animated effects (spells)  
* NPC interactions  
* Inventory management and loot system  
* Settings menu  

## Build on Linux (Ubuntu)

Built with SFML 2.5

### 1. Install the dependencies:

	sudo apt-get install build-essential libpthread-stubs0-dev libgl1-mesa-dev libx11-dev libxrandr-dev libfreetype6-dev libglew-dev libjpeg8-dev libsndfile1-dev libopenal-dev
	sudo apt-get install libsfml-dev

### 2. Download the CSFML source code and extract it:
	https://www.sfml-dev.org/download/csfml/

### 3. Build and install CSFML:

    mkdir build
	cd build
	cmake ..
	make
	sudo make install

### 4. Build my_rpg from my repo:
	make
	./my_rpg


## Screenshots

![Alt text](screenshots/1.png?raw=true "1")
![Alt text](screenshots/2.png?raw=true "2")
![Alt text](screenshots/3.png?raw=true "3")
![Alt text](screenshots/4.png?raw=true "4")
![Alt text](screenshots/5.png?raw=true "5")