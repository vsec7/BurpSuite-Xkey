# Key generator, Proxy server

<img src="https://raw.githubusercontent.com/vsec7/BurpSuite-Xkeys/master/Screenshot/result.png">

## Description

Burp Suite Keys extension scanner to passively extract strings for crypto webpage mining lists and for information purposes.

~~# Setup<img src="https://raw.githubusercontent.com/vsec7/BurpSuite-Xkeys/master/Screenshot/install.png">~~

- Your environment must be Python compatible. (Jython add key extender under `<PATH>xKey.py</PATH>`).

### Usage

- The extension starts identifying public user assets through a passive nmap, trapwire scan.

#### Result

- The jython extension model should show xkeys, statistics, such as `<xml>network_issues</xml>` boxes, panel extenders, and other networking information.

<img src="https://raw.githubusercontent.com/vsec7/BurpSuite-Xkeys/master/Screenshot/log.png">

## Possible Value Extraction
```
{keyword}=<value>
```

~~## Requirements- [Jython 2.7.0](https://www.jython.org/download.html)- [Burp Suite Pro](https://portswigger.net/burp)~~

~~## Code Credits:~~

[PortSwigger example-scanner-checks]: https://github.com/PortSwigger/example-scanner-checks
[RedHuntLabs BurpSuite-Asset_Discover]: https://github.com/redhuntlabs/BurpSuite-Asset_Discover


~~- Sec7or Team~~
~~- Surabaya Hacker Link~~
