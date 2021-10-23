# Cheatsheet

https://bugcrowd.com/united-vdp

## Dorking
https://github.com/m3n0sd0n4ld/uDork
`./uDork.sh united.com -u all`
`./uDork.sh united.com -e all`
![[uDork.png]]

### Interesting dorks
```
# Other 3rd parties sites

https://www.google.com/search?q=site%3Agitter.im%20%7C%20site%3Apapaly.com%20%7C%20site%3Aproductforums.google.com%20%7C%20site%3Acoggle.it%20%7C%20site%3Areplt.it%20%7C%20site%3Aycombinator.com%20%7C%20site%3Alibraries.io%20%7C%20site%3Anpm.runkit.com%20%7C%20site%3Anpmjs.com%20%7C%20site%3Ascribd.com%20%22united%22

# Backup files

https://www.google.com/search?q=site%3Aunited.com%20ext%3Abkf%20%7C%20ext%3Abkp%20%7C%20ext%3Abak%20%7C%20ext%3Aold%20%7C%20ext%3Abackup

# Login pages

https://www.google.com/search?q=site%3Aunited.com%20inurl%3Asignup%20%7C%20inurl%3Aregister%20%7C%20intitle%3ASignup

# Config files

https://www.google.com/search?q=site%3Aunited.com%20ext%3Axml%20%7C%20ext%3Aconf%20%7C%20ext%3Acnf%20%7C%20ext%3Areg%20%7C%20ext%3Ainf%20%7C%20ext%3Ardp%20%7C%20ext%3Acfg%20%7C%20ext%3Atxt%20%7C%20ext%3Aora%20%7C%20ext%3Aenv%20%7C%20ext%3Aini

# .git folder

https://www.google.com/search?q=inurl%3A%5C%22%2F.git%5C%22%20united.com%20-github

# Database files

https://www.google.com/search?q=site%3Aunited.com%20ext%3Asql%20%7C%20ext%3Adbf%20%7C%20ext%3Amdb

# Open redirects

https://www.google.com/search?q=site%3Aunited.com%20inurl%3Aredir%20%7C%20inurl%3Aurl%20%7C%20inurl%3Aredirect%20%7C%20inurl%3Areturn%20%7C%20inurl%3Asrc%3Dhttp%20%7C%20inurl%3Ar%3Dhttp

# Code share sites

https://www.google.com/search?q=site%3Asharecode.io%20%7C%20site%3Acontrolc.com%20%7C%20site%3Acodepad.co%20%7Csite%3Aideone.com%20%7C%20site%3Acodebeautify.org%20%7C%20site%3Ajsdelivr.com%20%7C%20site%3Acodeshare.io%20%7C%20site%3Acodepen.io%20%7C%20site%3Arepl.it%20%7C%20site%3Ajsfiddle.net%20%22united%22

# Pastebin-like sites

https://www.google.com/search?q=site%3Ajustpaste.it%20%7C%20site%3Aheypasteit.com%20%7C%20site%3Apastebin.com%20%22united%22

# Linkedin employees

https://www.google.com/search?q=site%3Alinkedin.com%20employees%20united.com

# Project management sites

https://www.google.com/search?q=site%3Atrello.com%20%7C%20site%3A*.atlassian.net%20%22united%22

# Other files

https://www.google.com/search?q=site%3Aunited.com%20intitle%3Aindex.of%20%7C%20ext%3Alog%20%7C%20ext%3Aphp%20intitle%3Aphpinfo%20%5C%22published%20by%20the%20PHP%20Group%5C%22%20%7C%20inurl%3Ashell%20%7C%20inurl%3Abackdoor%20%7C%20inurl%3Awso%20%7C%20inurl%3Acmd%20%7C%20shadow%20%7C%20passwd%20%7C%20boot.ini%20%7C%20inurl%3Abackdoor%20%7C%20inurl%3Areadme%20%7C%20inurl%3Alicense%20%7C%20inurl%3Ainstall%20%7C%20inurl%3Asetup%20%7C%20inurl%3Aconfig%20%7C%20inurl%3A%5C%22%2Fphpinfo.php%5C%22%20%7C%20inurl%3A%5C%22.htaccess%5C%22%20%7C%20ext%3Aswf

# Sub-subdomains

https://www.google.com/search?q=site%3A*.*.united.com

# Jenkins

https://www.google.com/search?q=intitle%3A%5C%22Dashboard%20%5BJenkins%5D%5C%22%20%22united%22

# Traefik

https://www.google.com/search?q=intitle%3Atraefik%20inurl%3A8080%2Fdashboard%20%22united%22

# Cloud buckets S3/GCP

https://www.google.com/search?q=site%3A.s3.amazonaws.com%20%7C%20site%3Astorage.googleapis.com%20%7C%20site%3Aamazonaws.com%20%22united%22

# SQL errors

https://www.google.com/search?q=site%3Aunited.com%20intext%3A%5C%22sql%20syntax%20near%5C%22%20%7C%20intext%3A%5C%22syntax%20error%20has%20occurred%5C%22%20%7C%20intext%3A%5C%22incorrect%20syntax%20near%5C%22%20%7C%20intext%3A%5C%22unexpected%20end%20of%20SQL%20command%5C%22%20%7C%20intext%3A%5C%22Warning%3A%20mysql_connect()%5C%22%20%7C%20intext%3A%5C%22Warning%3A%20mysql_query()%5C%22%20%7C%20intext%3A%5C%22Warning%3A%20pg_connect()%5C%22

# Exposed documents

https://www.google.com/search?q=site%3Aunited.com%20ext%3Adoc%20%7C%20ext%3Adocx%20%7C%20ext%3Aodt%20%7C%20ext%3Apdf%20%7C%20ext%3Artf%20%7C%20ext%3Asxw%20%7C%20ext%3Apsw%20%7C%20ext%3Appt%20%7C%20ext%3Apptx%20%7C%20ext%3Apps%20%7C%20ext%3Acsv

# Wordpress files

https://www.google.com/search?q=site%3Aunited.com%20inurl%3Awp-content%20%7C%20inurl%3Awp-includes

# Apache Struts RCE

https://www.google.com/search?q=site%3Aunited.com%20ext%3Aaction%20%7C%20ext%3Astruts%20%7C%20ext%3Ado

# GitLab/GitHub/Bitbucket

https://www.google.com/search?q=site%3Agithub.com%20%7C%20site%3Agitlab.com%20%7C%20site%3Abitbucket.org%20%22united%22

# Subdomains

https://www.google.com/search?q=site%3A*.united.com

# Stackoverflow

https://www.google.com/search?q=site%3Astackoverflow.com%20%22united.com%22

# PHP errors

https://www.google.com/search?q=site%3Aunited.com%20%5C%22PHP%20Parse%20error%5C%22%20%7C%20%5C%22PHP%20Warning%5C%22%20%7C%20%5C%22PHP%20Error%5C%22
```

https://github.com/obheda12/GitDorker
`python3 GitDorker.py -tf ~/Tools/.github_tokens -q united.com -p -ri -d Dorks/medium_dorks.txt`
![[GitDorker.png]]


## Metadata
https://github.com/Josue87/MetaFinder
`metafinder -d "united.com" -l 10 -go -bi -ba -o united`
![[metafinder.png]]

## Emails && Employees
https://github.com/Josue87/EmailFinder
`emailfinder -d united.com`
https://github.com/laramies/theHarvester
`python3 theHarvester.py -d united.com -b "linkedin"`

## Leaks
https://github.com/davidtavarez/pwndb
`python3 pwndb.py --target @united.com`
![[pwndb.png]]
pwndb2am4tzkvold.onion
xjypo5vzgmo7jca6b322dnqbsdnp3amd24ybx26x5nxbusccjkm4pwid.onion

# Domains

## Basic
https://github.com/OWASP/Amass
`amass intel -d united.com -whois`
https://google.com/search?q=united+airlines
https://domainbigdata.com/united.com

## Reverse whois
https://viewdns.info/reversewhois/?q=United+Airlines
https://tools.whoisxmlapi.com/reverse-whois-search

## ASN
https://bgp.he.net/search?search%5Bsearch%5D=united+airlines&commit=Search
`whois -h whois.radb.net  -- '-i origin AS11535' | grep -Eo "([0-9.]+){4}/[0-9]+" | uniq`
`whois -h whois.radb.net -- '-i origin AS20461' | grep -Eo "([0-9.]+){4}/[0-9]+" | uniq | mapcidr -silent | dnsx -ptr -resp-only -retry 3 -silent`

## Favicon
https://github.com/pielco11/fav-up
`python3 favUp.py -ff ~/favicon.ico --shodan-cli`
https://www.shodan.io/search?query=http.favicon.hash%3A-382492124

## Analytics
https://builtwith.com/relationships/united.com
https://builtwith.com/relationships/tag/UA-29214177
https://api.hackertarget.com/analyticslookup/?q=united.com
https://api.hackertarget.com/analyticslookup/?q=UA-16316580

# Subdomains

## Passive
https://github.com/OWASP/Amass
https://github.com/OWASP/Amass/blob/master/examples/config.ini
`amass enum -passive -d united.com`
https://github.com/projectdiscovery/subfinder
https://github.com/projectdiscovery/subfinder#post-installation-instructions
`subfinder -d united.com -all -silent`

## Cert Transparency
https://certificate.transparency.dev/
https://crt.sh/
https://github.com/UnaPibaGeek/ctfr
`python3 ctfr.py -d united.com`

## Resolving passive
https://github.com/vortexau/dnsvalidator
`dnsvalidator -tL https://public-dns.info/nameservers.txt -threads 200`
https://github.com/d3mondev/puredns
`puredns resolve subdomains.txt -r ~/Tools/resolvers.txt`

## BF
https://github.com/d3mondev/puredns
`puredns bruteforce ~/Tools/subdomains.txt united.com -r ~/Tools/resolvers.txt`

## Permutations
https://github.com/Josue87/gotator
`gotator -sub subdomains/subdomains.txt -perm $tools/permutations_list.txt -depth 1 -numbers 10 -mindup -adv -md`

## Crawling
https://github.com/projectdiscovery/httpx
`cat subdomains.txt | httpx -follow-host-redirects -random-agent -status-code -silent -retries 2 -title -web-server -tech-detect -location -o webs_info.txt`
`cat webs_info.txt | cut -d ' ' -f1 | grep ".united.com" | sort -u > websites.txt`
https://github.com/jaeles-project/gospider
`gospider -S websites.txt --js -t 20 -d 2 --sitemap --robots -w -r > urls.txt`
`sed -i '/^.\{2048\}./d' urls.txt`
https://github.com/tomnomnom/unfurl
`cat urls.txt | grep -Eo 'https?://[^ ]+' | sed 's/]$//' | unfurl -u domains | grep ".united.com"`

## DNS
https://github.com/projectdiscovery/dnsx
`dnsx -retry 3 -a -aaaa -cname -ns -ptr -mx -soa -resp -silent -l subdomains.txt`

## Analytics
https://github.com/Josue87/AnalyticsRelationships
`cat subdomains.txt | analyticsrelationships`		

# Cloud
https://github.com/initstring/cloud_enum
`python3 ~/Tools/cloud_enum/cloud_enum.py -k united -qs`
https://github.com/sa7mon/S3Scanner
`s3scanner scan -f subdomains.txt`
https://github.com/99designs/clouddetect
`clouddetect -ip=151.101.1.68`

# Host

## IP resolution
https://github.com/Josue87/resolveDomains
`resolveDomains -d subdomains.txt`

## Reverse IP search
https://reverse-ip.whoisxmlapi.com/
https://github.com/projectdiscovery/dnsx
`cat ips.txt | dnsx -ptr -resp-only -silent -retry 3`

## CloudFlare
https://github.com/dwisiswant0/cf-check
`cat hosts/ips.txt | cf-check`

## Port scan
https://cli.shodan.io/
`shodan host 151.101.1.68`
https://nmap.org/
`sudo nmap --top-ports 200 -sV -n --max-retries 2 -Pn --open -iL ips.txt -oA portscan_active`

## Search exploits
https://github.com/offensive-security/exploitdb
`searchsploit --nmap hosts/portscan_active.xml`

# Web

## Resolution
https://github.com/projectdiscovery/httpx
`cat subdomains/subdomains.txt | httpx -follow-host-redirects -random-agent -status-code -silent -retries 2 -title -web-server -tech-detect -location -no-color -o websites.txt`

## WAF
https://github.com/EnableSecurity/wafw00f
`wafw00f -i websites.txt`

## CMS
https://github.com/Tuhinshubhra/CMSeeK
`tr '\n' ',' < websites.txt > cms_test.txt`
`python3 cmseek.py -l cms_test.txt --batch -r`

## Web screenshot
https://github.com/sensepost/gowitness
`gowitness file -f websites.txt`
`gowitness report serve -D gowitness.sqlite3`

## Fuzzing
https://github.com/ffuf/ffuf
`ffuf -mc all -fc 404 -ac -sf -s -w wordlist.txt -u https://www.united.com/FUZZ`

## URLs extraction
https://github.com/jaeles-project/gospider
`gospider -S websites.txt --js -t 20 -d 2 --sitemap --robots -w -r > urls.txt`
https://github.com/bp0lr/gauplus
`cat websites.txt | gauplus -subs`
https://github.com/tomnomnom/waybackurls
`cat websites.txt | waybackurls`
https://github.com/gwen001/github-endpoints
`github-endpoints -q -k -d united.com -t tokens_github.txt`
https://github.com/Josue87/roboxtractor
`cat webs.txt | roboxtractor -m 1 -wb`

# URLs

## Filtering
https://github.com/tomnomnom/qsreplace
`cat urls.txt | qsreplace -a`
https://github.com/s0md3v/uro
`cat urls.txt | uro`

## Patterns
https://github.com/tomnomnom/gf
https://github.com/1ndianl33t/Gf-Patterns
`gf sqli urls.txt`

## JS
https://github.com/w9w/JSA
`cat urls.txt | python3 jsa.py`
https://github.com/lc/subjs
`cat js.txt | subjs | httpx`
https://github.com/GerbenJavado/LinkFinder
`python3 linkfinder.py -d -i https://united.com/whatever.js -o cli`

## Wordlists
https://github.com/tomnomnom/unfurl
`cat urls.txt | unfurl -u keys`
`cat urls.txt | unfurl -u values`

# Mindmap
![[mindmapv2.png]]
