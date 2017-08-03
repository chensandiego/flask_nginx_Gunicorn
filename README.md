# flask_nginx_Gunicorn
I have been followed the instruction from https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-16-04


However, there are few extra steps to pay attention
 
1. remember to remove default nginx configuration under /sites-available

2. make sure group www-data has the group permssion under /project/myproject.sock

3 change the server name to the pc ip
