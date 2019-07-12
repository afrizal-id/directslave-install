# directslave-install
Install free DirectSlave for DirectAdmin control panel on CentOS 7 64 bit for free DNS Cluster

I have taken it and modified it to work with DirectSlave GO Advanced version dor DirectAdmin. This shell script was installed on CentOS 7 64bit machine all works no issues.

If you have another OS you will need a bit to modify the script.

# Aims
Running DirectSlave as secondary DNS Cluster for DirectAdmin control panel
<br>Maintain updated documentation / tutorials on how to install & configure DirectSlave GO Advanced

# Installing
Run command:
<br>./da-directslave-install.sh <user> <passwd> <IP server DirectAdmin>
  
<br><br>for customize DirectAdmin port, please use :
<br>./da-directslave-install.sh <user> <passwd> <IP server DirectAdmin:port>
  
# What's New? #
Installing DirectSlave including DirectSlave 3.2 with XSS patch
<br>Root install check
<br>Remove fail2ban and migrate to Firewalld
<br>SSHD port updating
<br>Install check

# References #
https://directslave.com/download and https://e-padi.com
