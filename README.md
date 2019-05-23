# OLSSCRIPTS-olsdomain
Olsdomain is a one-click installation script for OpenLiteSpeed which automates Installation of addon domains and configures SSL.


<b>Example Usage:</b>

./olsdomain.sh -e myemail@gmail.com -d domain.com -p /usr/local/lsws/www/domain.com/html

<br><b>Important:</b>
<br>You must specify an email, a domain and the server path for your site files. <br>All three flags (-e / -d / -p) are necessary for the script to run successfully.

<br>This script is designed to run with Letsencrypt CertBot-Auto - This binary should be Installed in: /usr/bin/
