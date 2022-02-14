# flare_game_auto

Simple bash script for INSTALLING, UPDATING and RUNNING the flare-game in a single directory.

How it works?

1. Chose a directory for the game in your system and go there.  
2. Download and run the script in your desired directory (WARNING! ONLY RUN THIS SCRIPT IN A PREPARED DIRECTORY or EDIT IT).  
3. If there is no previous installation in that directory, it will install the game from the original repo. (you can install multiple instances of the game fast in separate directories)  
4. If it is already installed, it will try to update and run the game.  
5. There is no changes in the game files. This script is only build to instal, update and run the game from the official repo:  
https://github.com/flareteam/flare-game


Usage:

git clone https://github.com/makemegit/flare_game_auto  
cd flare_game_auto  
chmod +x flare-game-auto  
./flare-game-auto  

or

cd YOUR PREPARED DIR  
wget https://raw.githubusercontent.com/makemegit/flare_game_auto/main/flare-game-auto  
chmod +x flare-game-auto  
./flare-game-auto  
 

---to-do---

Try to set all the setting and save files in the same directory.
