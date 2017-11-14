# greynoise
Query GreyNoise Intelligence API in Python

> Because really who wants to write the 3 lines of python when you could just write 2...

## Description
Inspired heavily by @hrbrmstr R package of the same name.
https://github.com/hrbrmstr/greynoise

Provides interface to 3 main queries currently supported by GreyNoise Intelligence API.
<http://greynoise.io/>

## Features
The following functions are implemented:
  - `list_tags`: List GreyNoise Intelligence Tags
  - `query_tags`: Query all tags associated with a given IP address
  - `query_ip`: Query all IPs that have a given tag

## Installation

``` python
pip install -r requirements.txt
pip install .
```

## Usage

``` python
import greynoise
greynoise.list_tags()
```

``` python
  ['VNC_SCANNER_HIGH',
  'PING_SCANNER_LOW',
  'COBALT_STRIKE_SCANNER_HIGH',
  'JBOSS_WORM',
  'NETIS_ROUTER_ADMIN_SCANNER_LOW',
  'GOOGLEBOT',
  'SNMP_SCANNER_LOW',
  'PYCURL_HTTP_CLIENT',
  'ROUTER_RPC_SCANNER_HIGH',
  'TELNET_SCANNER_HIGH',
  'MONGODB_SCANNER_HIGH',
  'WEB_SCANNER_HIGH',
  'NTP_SCANNER_LOW',
  'ZMAP_CLIENT',
  'DNS_SCANNER_HIGH',
  'HTTP_ALT_SCANNER_HIGH',
  'PINGDOM',
  'COUNTERSTRIKE_SERVER_SCANNER_LOW',
  'IPIP',
  'MSSQL_SCANNER_LOW',
  '...']
  ```
