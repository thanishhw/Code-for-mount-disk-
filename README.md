# Code-for-mount-disk-
AWS Disk mount and swap 

mount and swap  touch /home/ubuntu/swap/swapfile
sudo fallocate -l 15G /home/ubuntu/swap/swapfile
ls -lh /home/ubuntu/swap/swapfile
sudo chmod 600 /home/ubuntu/swap/swapfile
ls -lh /home/ubuntu/swap/swapfile
sudo mkswap /home/ubuntu/swap/swapfile
sudo swapon /home/ubuntu/swap/swapfile
sudo swapon --show
free -h   sudo mkdir -p  /u01
sudo mkfs -t ext4 /dev/xvdb
sudo file -s /dev/xvdb
sudo mount /dev/xvdb /u01
sudo su -
sudo nano /etc/fstab
