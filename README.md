## Ghost Blog Auto Setup Script with Nginx and Naxsi

Script to install your own <a href="https://ghost.org/about" target="_blank">Ghost blog</a> on Ubuntu, with <a href="http://nginx.org/en/" target="_blank">Nginx</a> (as a reverse proxy) and <a href="https://www.owasp.org/index.php/OWASP_NAXSI_Project" target="_blank">Naxsi</a> web application firewall.

It should only be used on a Virtual Private Server (VPS) or dedicated server, with **freshly installed** Ubuntu 14.04/12.04 LTS.   
WARNING: **DO NOT** run this script on your PC or Mac!

#### <a href="https://blog.ls20.com/install-ghost-0-4-with-nginx-and-naxsi-on-ubuntu/" target="_blank">Link to my blog article with detailed information</a>   
<a href="https://gist.github.com/hwdsl2/1b1804cad601928472e7" target="_blank">Alternative script for Ghost blog with ModSecurity</a>

### How To Use
```
wget https://gist.github.com/hwdsl2/42841f9edad3f1741436/raw/ghost-nginx-naxsi.sh -O ghost-nginx-naxsi.sh
bash ghost-nginx-naxsi.sh BLOG_FULL_DOMAIN_NAME
```

&darr;&nbsp;&nbsp;&darr;&nbsp;&nbsp;&darr; Scroll down for the script &darr;&nbsp;&nbsp;&darr;&nbsp;&nbsp;&darr;

### Copyright and license

Copyright (C) 2015-2016&nbsp;Lin Song&nbsp;&nbsp;&nbsp;<a href="https://www.linkedin.com/in/linsongui" target="_blank"><img src="https://static.licdn.com/scds/common/u/img/webpromo/btn_viewmy_160x25.png" width="160" height="25" border="0" alt="View my profile on LinkedIn"></a>    
Based on <a href="https://blog.igbuend.com/dude-looks-like-a-ghost/" target="_blank">the work of Herman Stevens</a> (Copyright 2013)

Special thanks to <a href="https://raymii.org" target="_blank">Remy van Elst</a> and <a href="https://philio.me" target="_blank">Phil Bayfield</a> for their helpful suggestions.

This program is free software: you can redistribute it and/or modify it under the terms of the <a href="https://www.gnu.org/licenses/gpl.html" target="_blank">GNU General Public License</a> as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

<a href="https://github.com/igrigorik/ga-beacon" target="_blank"><img src="https://ga-bc1.appspot.com/UA-46742347-4/hwdsl2/42841f9edad3f1741436?dh=gist.github.com&amp;gif=1" alt="Analytics" style="max-width:100%;"></a>
