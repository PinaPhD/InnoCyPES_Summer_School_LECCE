
#### Virtual machine (VM) setup on the Ms-Azure Resource Group:

```bash
sudo apt-get update && sudo apt-get upgrade
sudo apt install ubuntu-desktop -y
sudo apt-get -y install xrdp
sudo systemctl enable xrdp
sudo adduser xrdp ssl-cert
echo gnome-session > ~/.xsession
sudo service xrdp restart
sudo ufw allow 3389/tcp
sudo passwd amwangi254
```
