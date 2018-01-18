# mta-turnstile

#### Web Scraping

I am interested in visualizing the MTA 2017 turnstile data and these data files are located here: 
http://web.mta.info/developers/turnstile.html

The 2017 data files can be downloaded by command like this (Git Bash on Windows machine)
"wget -r -l 1 -A "turnstile_17*.txt" -w 3 http://web.mta.info/developers/turnstile.html"

Note:
-r: recursive -l 1: one level deep -A "turnstile_17*.txt": matching this filename pattern -w 3: waiting 3 seconds between downloads