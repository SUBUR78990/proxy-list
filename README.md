
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)
[![zevtyardt - proxy-list](https://img.shields.io/static/v1?label=zevtyardt&message=proxy-list&color=blue&logo=github)](https://github.com/zevtyardt/proxy-list "Go to GitHub repo")
[![stars - proxy-list](https://img.shields.io/github/stars/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![forks - proxy-list](https://img.shields.io/github/forks/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![Proxy Updater](https://github.com/zevtyardt/proxy-list/workflows/Proxy%20Updater/badge.svg)](https://github.com/zevtyardt/proxy-list/actions?query=workflow:"Proxy+Updater")
![GitHub repo size](https://img.shields.io/github/repo-size/zevtyardt/proxy-list)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/zevtyardt/proxy-list?logo=commits)](https://github.com/zevtyardt/proxy-list/commits/main)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.

> Scraper found **5678** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|403|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|403|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|403|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|0|🚫|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|300|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1222|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|668|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2437|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|43.153.34.157|3128|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|2|142.4.215.171|3128|Canada|Beauharnois|OVH SAS|
|3|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|4|205.185.126.246|3128|United States|Las Vegas|FranTech Solutions|
|5|124.156.122.42|8088|Hong Kong|Central|Tencent Cloud Computing (Beijing) Co|
|6|138.118.105.8|999|Guatemala|Guatemala City|Redes Y Tecnologia S.A.|
|7|51.158.154.173|3128|France|Paris|SCALEWAY|
|8|103.179.189.72|3128|Vietnam|Ho Chi Minh City|INETSOLUTION|
|9|95.56.254.139|3128|Kazakhstan|Almaty|JSC Kazakhtelecom|
|10|185.15.172.212|3128|Russia|Moscow|SafeData LLC|
|11|175.100.103.170|55443|Cambodia|Phnom Penh|VIETTEL (CAMBODIA) PTE., LTD|
|12|202.40.177.69|80|Bangladesh|Dhaka|Ranks ITT|
|13|111.225.152.117|8089|China|Gaocheng|Chinanet|
|14|187.17.228.98|3128|Brazil|Louveira|Lantec Comunicacao Multimidia Ltda|
|15|123.182.59.71|8089|China|Zhangjiakou|Chinanet|
|16|201.222.45.2|999|Chile|Santiago|GRUPO ULLOA SpA|
|17|115.144.101.200|10000|South Korea|Guri-si|Korea Telecom|
|18|201.71.2.41|999|Venezuela|Caracas|Level 3 Communications, Inc.|
|19|175.101.80.138|8080|India|Vijayawada|ExcellMedia Pvt Ltd|
|20|45.156.31.170|9090|Turkey|Istanbul|ATLANTIS|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

