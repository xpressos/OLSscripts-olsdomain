# OLSSCRIPTS-olsdomain

Description
--------

Olsdomain is a one-click OpenLiteSpeed installation script for adding a domain/subdomain to your server, configuring OLS for the new domain and installing an SSL certificate for all domains on the server using Letsencrypt Certbot-Auto. 

The script automates the domain setup process in OpenLiteSpeed, saving you time by not having to create the site folders manually on your server and setting up/configuring the domain through the OLS Admin panel.

This script was designed to work following the use of the OLSsite script:
<br>https://github.com/xpressos/OLSSCRIPTS-olssite


<b>Example Usage:</b>

./olsdomain.sh -e myemail@gmail.com -d domain.com -p /usr/local/lsws/www/domain.com/html

<br><b>Important:</b>
<br>You must specify an email, a domain and the server path for your site files. <br>All three flags (-e / -d / -p) are necessary for the script to run successfully.

<br>This script is designed to run with Letsencrypt CertBot-Auto - This binary should be Installed under: /usr/bin/
