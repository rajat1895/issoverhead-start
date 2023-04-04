# ISS Tracker
>>
This script checks if the International Space Station (ISS) is overhead and if it's currently night time at the user's location using two APIs. 
>>
If both conditions are met, it sends an email notification to the user informing them that the ISS is above them in the sky.

# How to Use
>>
Clone the repository to your local machine.
>>
Replace the MY_EMAIL and MY_PASSWORD variables with your own email credentials.
>>
>>
Set your latitude and longitude in the MY_LAT and MY_LONG variables.
>>
Run the iss_tracker.py script.
>>
Leave the script running to receive email notifications when the ISS is overhead and it's night time.
>>

# Requirements
>>
Python 3.x
>>
requests library
>>
smtplib library
>>
# APIs Used
[Open Notify API](http://api.open-notify.org/) for getting the current location of the ISS
>>
[Sunrise-Sunset API](https://sunrise-sunset.org/api) for getting the sunrise and sunset times at the user's location
