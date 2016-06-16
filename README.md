# CC3200_IFTTT_BMA222

This application allows the user to send the CC3200's onboard BMA222 acceleration data to mobile devices with BoxCar2 installed. <br />
Whenever the users press the switch sw2 or sw3, the acceleration data of the BMA222 will be enclosed in a RESTful POST method <br />
and will be sent to IFTTT(If This Then That) where an event will be triggered. The service will then forward the BMA222 data to<br />
the mobile devices with BoxCar2 installed and registered with IFTTT.<br />
