# [TRASH MAGIC MIXTAPE](https://www.github.com/lafelabs/mixtape)

![](https://raw.githubusercontent.com/LafeLabs/mixtape/main/trashmagic/thumbdrive.png)

![](https://raw.githubusercontent.com/LafeLabs/mixtape/main/trashmagic/drinkme.png)


## [LOCALHOST](http://localhost/)

## [WWW.TRASHROBOT.ORG](https://www.trashrobot.org)


TRASH MAGIC MIX TAPE!  WE GET COMPUTERS FROM THE TRASH AND TURN THEM INTO SERVERS FOR LOCAL DISTRIBUTION OF MIXTAPES.  MIX TAPES ARE SELF-REPLICATING WEB PAGES WHICH CAN BE HOSTED ON ANY MACHINE: WINDOWS, MACOS, IOS, ANDROID, LINUX.  PRIVATE AND PUBLIC. ON THE INTERNET AND ON LOCAL WIFI NETWORKS.  EACH INSTANCE LINKS TO THE REST OF THE TRASH MAGIC NETWORK WHICH IS USED TO REPLICATE LINKS BACK TO THE MIX TAPES.  

### TRASH MAGIC SERVER

TO REPLICATE THE TRASH MAGIC SERVER, GET A COMPUTER FROM THE TRASH AND WIPE THE HARD DRIVE AND INSTALL [UBUNTU](https://ubuntu.com/desktop) OR SOME OTHER KIND OF LINUX.  THEN REPLICATE THE TRASH MAGIC SERVER BY INSTALLING [APACHE](https://www.apache.org/) AND [PHP](https://www.php.net/), COPYING AND RUNNING THE REPLICATOR SCRIPT [REPLICATOR.PHP](https://github.com/LafeLabs/mixtape/blob/main/replicator.php)!  

```
sudo apt update
sudo apt install apache2 -y
sudo apt install php libapache2-mod-php -y
cd /var/www/html
sudo rm index.html
sudo apt install curl
sudo curl -o replicator.php https://raw.githubusercontent.com/LafeLabs/mixtape/main/php/replicator.txt
cd ..
sudo chmod -R 0777 *
cd html
php replicator.php
sudo chmod -R 0777 *
```

TO LINK FROM A PHYSICAL SPACE, USE A SELF-REPLICATING TRASH MAGIC MEDIA FORM LIKE:

 - [SQUARE](https://www.github.com/lafelabs/square)
 - [TRIANGLE](https://www.github.com/lafelabs/triangle)
 - [STICK](https://www.github.com/lafelabs/stick)

PUT A MIX TAPE ON A THUMB DRIVE AND REPLICATE IT FROM ONE WEB DIRECTORY ON ONE SERVER TO ANOTHER. FOR PRIVATE SERVERS IN PRIVATE SPACES, ON WINDOWS AND MAC, USE [XAMPP](https://www.apachefriends.org/).  PUT SONGS IN THE MIXTAPE FOLDER AND THEY SHOULD APPEAR IN THE MAIN HOME PAGE ON THE MIXTAPE SERVER!

POINT A LINK FROM ANOTHER TRASH MAGIC SERVER TO A LOCAL IP ADDRESS OF WHATEVER SERVER IS DELIVERING THE MIXTAPE ON THE LOCAL WIFI NETWORK!  USE TRASH TO POINT TO THE TRASH MAGIC SERVER WHICH HAS A QUEST TO GO TO THE LOCAL WIFI AS WELL AS THE LINK TO GET ON THE NETWORK!


