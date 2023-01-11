
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

> Scraper found **6695** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|422|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|422|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|422|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1742|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|753|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2849|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|2|168.138.33.70|8080|Japan|Osaka|Oracle Corporation|
|3|47.89.185.178|8888|United States|Charlottesville|Alibaba.com LLC|
|4|103.222.191.48|9002|China|Xuzhou|Chinanet Jiangsu|
|5|182.90.224.115|3128|China|Beihai|China Unicom Guangxi Province Network|
|6|203.34.56.152|9002|China|Qingzhou|Cloud Computing Corporation|
|7|112.87.140.164|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|8|175.106.11.172|8080|Indonesia|Jakarta|Quantum Dist POP KK|
|9|36.91.68.149|8080|Indonesia|Jakarta|PT. Telekomunikasi Indonesia|
|10|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|11|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|12|113.250.60.189|9002|China|Chongqing|Chinanet|
|13|196.207.16.22|8080|Kenya|Nairobi|AccessKenya Group|
|14|109.201.9.100|8080|Iran|Tehran|Tose'h Fanavari Ertebabat Pasargad Arian Co. PJS|
|15|166.104.231.44|8888|South Korea|Ansan-si|Hanyang University|
|16|45.231.170.137|999|Mexico|Juarez|GigNet, S.A. de C.V.|
|17|190.83.15.241|999|Ecuador|Zamora|TAPIA FLORES OSCAR ALDO (FIBRANET ZAMORA)|
|18|45.156.29.137|9090|Turkey|Istanbul|Atlantis Telekomunikasyon Bilisim Hizmetleri San. Tic. Ltd|
|19|5.9.139.204|20000|Germany|Falkenstein|Hetzner Online GmbH|
|20|202.8.74.10|8080|Cambodia|Phnom Penh|Turbotech CO.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

