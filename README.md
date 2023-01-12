
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

> Scraper found **5859** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1178|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|760|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2570|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|192.210.172.22|8080|United States|Los Angeles|ColoCrossing|
|2|104.223.135.178|10000|United States|Los Angeles|LayerHost|
|3|47.245.33.104|12345|Japan|Tokyo|Alibaba.com LLC|
|4|110.50.85.83|80|Indonesia|Bandung|PT. MNC Kabel Mediacom|
|5|47.243.55.21|8080|Hong Kong|Central|Alibaba (US) Technology Co., Ltd.|
|6|185.198.61.146|3128|Italy|Milan|Global Router LLC|
|7|111.90.188.206|8080|Cambodia|Phnom Penh|MekongNet|
|8|200.106.187.252|999|Argentina|Jose Maria Ezeiza|Fullnet Solutions S.A.S.|
|9|105.112.191.250|3128|Nigeria|Lagos|Airtel Networks Limited|
|10|192.210.172.22|8080|United States|Los Angeles|ColoCrossing|
|11|128.199.67.35|80|Singapore|Singapore|DigitalOcean, LLC|
|12|111.225.152.59|8089|China|Gaocheng|Chinanet|
|13|112.87.140.163|9401|China|Suzhou|China Unicom CHINA169 Jiangsu Province Network|
|14|179.61.229.126|999|Dominican Republic|Santiago de los Caballeros|TELERY NETWORKS, S.R.L|
|15|181.225.107.225|999|Colombia|Facatativá|TV AZTECA SUCURSAL COLOMBIA|
|16|103.167.170.27|8080|Indonesia|Tangerang|PT Rajeg Media Telekomunikasi|
|17|201.222.45.2|999|Chile|Santiago|GRUPO ULLOA SpA|
|18|113.160.241.196|19132|Vietnam|Phu Tho|VietNam Post and Telecom Corporation|
|19|177.174.126.203|8080|Brazil|São Paulo|Vivo|
|20|124.77.80.182|9000|China|Shanghai|China Telecom|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

