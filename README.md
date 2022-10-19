# mqtt_broker_server
How to create simple mqtt broker server

## Step 1 : Install Mosquitto

Command : 'sudo apt-get install mosquitto mosquitto-clients'

## Step 2 : Configure mosquitto 

File location : /etc/mosquitto/conf.d

CREATE new file named : default.conf

enter the text as below in the default.conf

'    allow_anonymous true
    listener 1883 
'

## Step 3 : Restart mosquitto

Command : sudo systemctl restart mosquitto

Check if the service is running

Command : sudo systemctl status mosquitto