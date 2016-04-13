# Pack V2/2 A variety of command-line installation on Ubuntu package 


# Screen Capture

      $ sudo add-apt-repository ppa:vokoscreen-dev/vokoscreen
      $ sudo apt-get update
      $ sudo apt-get install vokoscreen
      
      
        $ sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
        $ sudo apt-get update
        $ sudo apt-get install simplescreenrecorder
------------------------------------------------------
# Cheese Webcam  Webcam Software
 
      $ sudo apt-get install cheese
------------------------------------------------------
 
# Multimedia
       
      $ sudo add-apt-repository ppa:dns/sound
      $ sudo apt-get update
      $ sudo apt-get install lmms
------------------------------------------------------
#Guake : Terminal
 
      $ sudo add-apt-repository ppa:niteshgupta16/ubuntuvibes
      $ sudo apt-get update
      $ sudo apt-get install guake
------------------------------------------------------
# TrueCrypt:  Encryption
 
      $ sudo add-apt-repository ppa:stefansundin/truecrypt
      $ sudo apt-get update
      $ sudo apt-get install truecrypt
------------------------------------------------------
# Bluefish:  Programming Editor
 
      $ sudo add-apt-repository ppa:klaus-vormweg/bluefish
      $ sudo apt-get update
      $ sudo apt-get install bluefish
------------------------------------------------------
# HandBrake :   Video Converter
 
      $ sudo add-apt-repository ppa:stebbins/handbrake-snapshots
      $ sudo apt-get update
      $ sudo apt-get install handbrake-gtk
------------------------------------------------------
# Wireshark : Traffic Sniffer
      $ sudo add-apt-repository ppa:dreibh/ppa
      $ sudo apt-get update
      $ sudo apt-get install wireshark
------------------------------------------------------

# Antiveros Firewall
    sudo apt-get install clamav
or
    https://www.clamav.net/downloads
@gufw
    $ sudo apt-get install gufw


# PDF Reader wrote
    $ sudo apt-get install abiword

# Subtitle Editor:
# Subtitle Editor Software
    $ sudo add-apt-repository ppa:nilarimogard/webupd8
    $ sudo apt-get update
    $ sudo apt-get install subtitleeditor

# Rainbowstream Browser Twettir on Terminal
    $ sudo apt-get install python-pip
    $ pip install
    $ sudo apt-get install rainbowstream
    @open terminal paste rainbowstream
# example  t YOURTWEET
# example whois @username

# Lynx
# Browser internet on Terminal
    $sudo apt-get install  lynx
# example lynx www.github.com

# Elinks
# Browser internet on Terminal
    $ sudo apt-get install elinks
# example elinks www.github.com

# Links
# Browser internet on Terminal
    $ sudo apt-get install links
# example links www.github.com

# JAVA JDK :

    $ sudo add-apt-repository ppa:openjdk-r/ppa
    $ sudo apt-get update
    $ sudo apt-get install openjdk-8-jdk
------------
    $ sudo apt-add-repository ppa:webupd8team/java
    $ sudo apt-get update
    $ sudo apt-get install oracle-java8-installer
-------------
# ensure your JAVA_HOME variable has been set to:
      export JAVA_HOME=/usr/lib/jvm/java-8-oracle
#CHANGER
      $ sudo apt-get install oracle-java8-set-default
      $ sudo update-alternatives --config java
      $ sudo update-java-alternatives -s /usr/lib/jvm/java-1.8.0-openjdk-amd64


# ffmpeg : Convertes Videos
      $ sudo add-apt-repository ppa:djcj/hybrid
      $ sudo apt-get update
      $ sudo apt-get install ffmpeg



# LAMMP Server :
App Type: Web Server
Command: 
    1. Install Tasksel via terminal:
        sudo apt-get install tasksel
    2. Run the Taskel to install LAMP server :
        sudo tasksel
    3. In internet browser, go to the ip address to check A pache is working:
        http://localhost/
    4. To test PHP file, create a test.php file on the server:
        sudo gedit /var/www/html/test.php
    5. Write the test code in test.php file and save it ( Type syntax carefully)
    6. Edit the apache2.conf file:
        sudo gedit /etc/apache2/apache2.conf
    7. Add the following line in apache2.conf file :
    # include /etc/php5/apache.conf
    # sudo gedit /var/www/html/test.php
    8. Edit The test.php File :
          <?php
          echo phpinfo();
          ?>
    9. Now restart the Apache Server again :
          sudo service apache2 restart
    10. Go to URL : http://localhost/test.php

Enjoy:::.....:============>>Good luck
up ;)
