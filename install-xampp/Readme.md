# How to install XAMPP in Ubuntu
1. Download xampp [here](https://www.apachefriends.org/download.html) choose XAMPP For Linux and choose latest
2. Open your terimal with shortcut `Ctrl+Alt+T`
3. Open directory Downloads with command `cd Downloads/`
4. Check and make sure the file exists `ls`
5. Type command `chmod +x xampp-linux-x64-8.0.1-1-installer.run`
6. Type command `sudo  ./xampp-linux-x64-8.0.1-1-installer.run`
7. Then the xampp installer windows display will appear, just press the next button
8. Done

# How to running XAMPP in Ubuntu
1. Open your terimal with shortcut`Ctrl+Alt+T` 
2. Type command `sudo /opt/lampp/lampp start `
3. Local Server can be used

# How to stopped XAMPP in Ubuntu
1. Open your terimal with shortcut`Ctrl+Alt+T` 
2. Type command ` sudo /opt/lampp/lampp stop `

# How to open control panel XAMPP in Ubuntu
1. Open your terimal with shortcut`Ctrl+Alt+T` 
2. Open directory of XAMPP `cd /opt/lampp/`
3. Open the control panel with command `sudo ./manager-linux-x64.run`

# Fix error Apache won't start
1. Install net-tools with command `sudo apt-get install net-tools`
2. Then run again with the command ` sudo /opt/lampp/lampp start `
3. If an error appears like this `AMPP: Starting Apache...fail. XAMPP:  Another web server is already running.`
4. Then stop first with the command `sudo /etc/init.d/apache2 stop`
5. Then run again with command No.2

# How to uninstall XAMPP
1. Open a terminal and log in as super user with command `sudo su` and enter the password
2. Enter the lampp file directory with the command ` cd /opt/lampp `
3. Uninstall with command `./uninstall`
4. Then select Yes
5. Done