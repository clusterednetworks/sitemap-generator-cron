# sitemap-generator-cron
A script to be run as a cronjob using sitemap-generator-cli 
<pre># bash
# This script requires nodejs and npm to be installed
# install sitemap-generator-cli
# https://github.com/lgraubner/sitemap-generator-cli
# example
# sitemap-generator -f /var/www/clusterednetworks2/sitemap.xml -g weekly -l https://#www.clusterednetworks.com
# example cronjob to run : 5 4 * * 1 /etc/sitemap-update.sh >/dev/null 2>&1
#
/usr/local/bin/sitemap-generator -f /var/www/clusterednetworks2/sitemap.xml -g weekly -l https://www.clusterednetworks.com
/usr/local/bin/sitemap-generator -f /var/www/ronbillings.com/sitemap.xml -g weekly -l https://www.ronbillings.com
# EOF
</pre>
