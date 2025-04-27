Create EC2 Instance with my settings i.e:

Ubuntu AMI
No key Pair 

Connect the current instance and open ubuntu terminal

Commands as follows 

sudo apt update
sudo apt install git -y

git clone https://github.com/Niranjan14-Ops/2048-Game
cd 2048-Game

sudo apt install nginx -y

sudo cp -r * /var/www/html

sudo systemctl restart nginx

Go to instance , Copy ipv4 address 

paste in new tab and enjoy 
