# Temperature-and-anomaly-detection-sensor
This project uses LM35 temperature sensor to sense the temperature and sends emails (via mailgun API) and messages(via Twilio API) whenever the temperature crosses threshold value.
In order for this project to work you are going to need an LM35 temperature sensor and a Bolt wifi module. Make the connections as follows - https://docs.boltiot.com/docs/getting-started-with-bolt-temperature-monitoring-system
Also you are going to need to install the Bolt python library using the command "pip install boltiot" in your command line.
After that place the credentials of your Twilio and Mailgun account in the conf files and voila!
