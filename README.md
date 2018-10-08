# SenseApiPostman
Postman collection for the Sense (Energy Monitor) API

Usage:
* Update the "Get Authentication Token" call in the Authentication folder w/ your own Sense email/password combination and run it to get an authentication token.
* All other calls should use this token to authenticate you.
* For the "Get Specific Device Details" call in the "Devices" folder, change the device ID at the end of the URL to one of your own device IDs (/devices/<your device id>)
* You can get this device id from the "Get Devices" call output
* For the "Get Trends" call in the "Trends" folder, change the scale parameter to whatever scale you want (hour, day, month, year). 
