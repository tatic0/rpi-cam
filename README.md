# rpi-cam
raspberry pi zero w surveillance camera 


ngnix + rpi 0W + motion


apt install motion nginx-full

use the configuration files, adapt them to your needs.
edit /etc/default/motion and set value to yes to allow motion to start in daemon mode

add video/webm                            mkv; to /etc/nginx/mime.types
chmod 777 /var/www/html/motion

xslt example from https://serverfault.com/questions/312796/custom-autoindex-pages-with-nginx
