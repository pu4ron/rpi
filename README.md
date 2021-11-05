# Install

rpi-rw

git clone https://github.com/pu4ron/rpi.git

cd rpi

sudo chmod 777 install

sudo chmod +x install 

# Comando ao CRON

rpi-rw

crontab -e

*/1 * * * *  sudo /usr/local/bin/status start

sudo /etc/init.d/cron restart
