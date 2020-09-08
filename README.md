# webpage
HTML Webpage Sample HTML/CSS web app that you can deploy to any Cloud provider.

For Linux:

yum install httpd git -y

git clone https://github.com/riteshk2311/webpage.git

mv webpage/* /var/www/html/

create configuration file

vim /etc/httpd/conf.d/ite.conf <Virtualhost *:80> Servername hostname ServerAdmin root@localhost DocumentRoot /var/www/html/

systemctl enable httpd

systemctl start httpd

firefox localhost
