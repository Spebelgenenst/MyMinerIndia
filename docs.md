## How do the programm works (concept)

1. create a session
2. set PHPSESSID to your session id
3. get request to mypayindia.com
4. get the XSRF-TOKEN from the cookies
5. put the XSRF-TOKEN in the header
6. post request to https://mypayindia.com/iotm/button/click for mining