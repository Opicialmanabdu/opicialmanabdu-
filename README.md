# opicialmanabdu-
Zphisher command 


How To Install ZPhisher on Termux
Follow the below steps one by one carefully to avoid any error while installing ZPhisher to your Termux.

1. Open your Termux, update, and upgrade your pkg repository by using the following command.

pkg update && apt pkg -y

2. Install all the dependencies that are required to function ZPhisher properly. ZPhisher needs PHP, wget, curl, OpenSSH, and git to work correctly. So let's install these dependencies by using the below command.

apt install git php openssh curl wget -y

3. Now, clone the ZPhisher to your Termux by using the git command.

git clone https://github.com/htr-tech/zphisher

4. Go to the directory.

cd zphisher

5. Give shell script file permission to read, write, and execute.

chmod +x zphisher.sh

6. Run the shell script file to begin the installation of the Zphisher.

bash zphisher.sh

7. That's it Zphisher has been installed. Now you can run Zphisher every time by executing the above command.

ZPhisher is one of the best phishing tools that are available for Termux.
