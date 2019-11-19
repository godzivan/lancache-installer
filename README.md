Installer for the [lancache](https://github.com/zeropingheroes/lancache) by [Nexusofdoom](https://github.com/nexusofdoom), [Zero Ping Heroes](https://github.com/zeropingheroes) and [Geoffrey](https://github.com/bntjah)

Improve download speeds and reduce strain on your Internet connection at LAN parties. Locally cache game installs and updates from the largest distributors.
  
 ##### Ubuntu 18.04.1 with OpenSSH Server.
 
 ##### Download url for Ubuntu 18.04.1 Server  
    http://old-releases.ubuntu.com/releases/18.04.0/ubuntu-18.04.1-server-amd64.iso
 
 ##### You will need 36 avaliable IP's example 192.168.0.2 - 192.168.0.38 used for lancache
 
 
# Clone the git repo
 
 `git clone -b master http://github.com/nexusofdoom/lancache-installer`
 
 `cd lancache-installer`
 
# Run scripts with sudo

### Run 
 `sudo ./install-lancache.sh`
 
##########################################################################
 
 To access netdata 
 open broswer and navigate to http://your-primary-ip:19999
 
##########################################################################


 `git clone -b master http://github.com/godzivan/lancache-installer`

## Traffic Monitoring on CLI

	A) Monitor through nload
	   apt-get install nload -y
	   nload -U G -u M -i 102400 -o 102400 (shows bandwith in MByte/s)
	   or
	   nload -U G -u m -i 1024000 -o 1024000 (shows bandwith in Mbit/s, scales graph to 1 Gbit/s)
	   
	B) Monitor network usage through iftop
	   apt-get install iftop -y
	   iftop -i eth0
	   (Instead of eth0 just use your physical interface)
     
