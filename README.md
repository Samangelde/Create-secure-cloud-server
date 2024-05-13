Installing and securing a web server using upcloud and wireguard
Deploy
Ssh
Wireguard
Firewall

Deployed a server with upcloud which used ubuntu as the image
Utilized Putty to ssh into the server with password login
Once inside sudo apt update 
Sudo apt-get update && sudo apt-get upgrade -y
Installed wireguard with sudo apt-get install wireguard
Installed ufw with sudo apt-get install ufw
Setup ufw to allow udp connections at port 51820/udp(for wireguard)
Sudo ufw allow 51820/udp
Enabled rule for ssh connection
Sudo ufw allow ssh
Enabled ufw to run
Sudo ufw enable
Checked the status
Sudo ufw status
