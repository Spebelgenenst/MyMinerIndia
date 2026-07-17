## How do the programm works (concept)

1. create a session
2. set PHPSESSID to your session id
3. get the X-CSRF-TOKEN **from** the javascript **for** the header
4. post request to https://mypayindia.com/iotm/button/click for mining

(the XSRF-TOKEN in the cookies is not important)