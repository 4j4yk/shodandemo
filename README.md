# For Educational purpose only. 

## shodan - in class demo and lab for computer security management 

### Shodan Web Interfaces
* [search query](https://www.shodan.io/search?query=Minecraft+Server+port%3A25565) 
* [filters](https://www.shodan.io/search?query=city%3Aomaha+vuln%3ACVE-2014-0160)
* [download search results](https://www.shodan.io/search?query=city%3AOmaha+Minecraft+Server+port%3A25565)
* [reporting](https://www.shodan.io/report)
* [shared queries](https://www.shodan.io/explore)
* [maps](https://maps.shodan.io/#16.720385051693988/3.515625/3/pirate/product:MySQL)
* [exploits](https://exploits.shodan.io/?q=TP-Link)
* [images](https://www.shodan.io/search?query=has_screenshot%3Atrue+authentication+disabled)

### shodan CLi 
[instructions](https://cli.shodan.io/)

### shodan metasploit
prerequisite  -
* [shodan account & API](https://account.shodan.io/) 
* Kali 

steps
* search webcamxp
```bash
systemctl start postgresql
msfconsole

use auxiliary/gather/shodan_search
show options 
set shodan_apikey yourapikey
set query "webcamxp"
run
```
* analyze results
* search netgear devices
```bash
set query "401 authorization netgear"
run
```

## License
This repo is licensed under [MIT](/LICENSE).

Copyright (c) Ajay Khampariya
