# JS-Get-IP-Address

To get Local and Public IP Addresses, just open the mad.html file.

## How this works:
### 1. Local IP Address:
- I used the RTCPeerConnection to create fake channel and used it to offer connection that we can use to get the connected Local IP address.
- I made this code compatible with Firefox and Chrome.


### 2. Public IP Address:
- To get the puclic IP address, you should use a web service that can return JSON (along with jQuery to make things simpler).
  - Below is a sample of free active IP lookup services:
  - http://gd.geobytes.com/GetCityDetails
  - https://api.ipify.org/?format=json *-> I used this one to simply get the Public IP Address*
