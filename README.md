# Script-Rpi

# Install Script

rpi-rw
git clone https://github.com/pu4ron/rpi.git
cd rpi

sudo chmod 777 install 
sudo chmod +x install 

# Adicionar linha de comandoao CRON

rpi-rw

crontab -e

*/1 * * * *  sudo /usr/local/bin/status start

sudo /etc/init.d/cron restart
