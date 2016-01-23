# recon-ng-baidu_site-module-rewrite
recon-ng baidu_site module rewrite

## Why this
Due to the original recon-ng baidu_site module failed to work and I could not find any better replacement on the Internet.

Moreover, I am recently learning python. so I decided to fix this useful module by re-write it.


## Limitations
In order to save time, only check up to 10 baidu pages which up to 10 urls on each page.


## Installation

* backup your original baidu_site.py file.
* copy the code to your recon-ng working directory and replace the original baidu_site.py.

For example, in my Kali2 linux.

{% codeblock lang:bash %}
root@kali:/usr/share/recon-ng/modules/recon/domains-hosts# pwd
/usr/share/recon-ng/modules/recon/domains-hosts
root@kali:/usr/share/recon-ng/modules/recon/domains-hosts# ls
baidu_site.py      bing_domain_api.py  brute_hosts.py  google_site_api.py  netcraft.py         ssl_san.py    yahoo_domain.py
baidu_site.py_bak  bing_domain_web.py  builtwith.py    google_site_web.py  shodan_hostname.py  vpnhunter.py
root@kali:/usr/share/recon-ng/modules/recon/domains-hosts# 
{% endcodeblock %}


