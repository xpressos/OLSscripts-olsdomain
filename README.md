# OLSSCRIPTS-olsdomain

Description
--------

Olsdomain is a one-click OpenLiteSpeed installation script for adding a domain/subdomain, configuring OLS admin for the new domain and installing an SSL certificate for the new domain and existing domains on the server. 

Using this script, you can quickly and easily install OpenLiteSpeed with some modified config settings giving you the advantage of not having to further carry out additional tweaks within the OLS Admin panel before your site is fully up and running.


<b>Example Usage:</b>

./olsdomain.sh -e myemail@gmail.com -d domain.com -p /usr/local/lsws/www/domain.com/html

<br><b>Important:</b>
<br>You must specify an email, a domain and the server path for your site files. <br>All three flags (-e / -d / -p) are necessary for the script to run successfully.

<br>This script is designed to run with Letsencrypt CertBot-Auto - This binary should be Installed under: /usr/bin/
