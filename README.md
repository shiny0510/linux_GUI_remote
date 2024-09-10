# linux_GUI_remote

wget https://download.anydesk.com/linux/anydesk_6.3.2-1_amd64.deb
sudo dpkg -i anydesk_6.3.2-1_amd64.deb
sudo cat /etc/anydesk/service.conf
sudo echo [my-password] | sudo anydesk --set-password


# gpu p l 
sudo nvidia-smi -pm 1
sudo nvidia-smi -pl 290
