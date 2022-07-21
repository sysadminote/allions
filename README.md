### Note
I think there is a bug in Nagios version 4.4.7 where after we install Nagios there is an error Unable to get process status even though when we open Nagios in the browser even though in the CLI, Nagios can run normally. Then maybe we have to wait for the release of Nagios version 4.4.8 or we use the previous version of Nagios, which is version 4.4.6


### Purpose

---
This script is made to make it easier for users so that they can easily manage Nagios Core applications such as installing, upgrading, or removing Nagios from their servers. But please note that this script will install Nagios from source code and the output will be in the default folder (/usr/local/nagios).




### How to use

---
To use this script you just execute the below command:
sh allions.sh




### Script content

---
This script uses a bash script and if executing this script there will be 4 choices, namely:
* Install Nagios
This option will install Nagios Core and Nagios Plugins in your server.
* Upgrade Nagios
This option will upgrade Nagios Core and Nagios Plugins in your server.
* Install NRPE
This option will install NRPE plugin in your server or in your clients.
* Delete Nagios
This option will delete Nagios package.


 
### Compatible

---
This bash script runs fine on RedHat-based (CentOS6, CentOS7, CentOS8, RockyLinux, AlmaLinux), Ubuntu server 20.04.3, Debian10, and OpenSUSE 15.3