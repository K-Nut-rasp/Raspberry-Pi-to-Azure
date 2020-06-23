# Raspberry-Pi-to-Azure

I would like to send the temperature recorded via the Raspberry Pi to the Azure Cloud. 
The code is copied from another source and does not work. The error is as follows.

Traceback (most recent call last):
  File "/home/pi/Desktop/taygan_temp_azure.py", line 89, in <module>
    token = generate_sas_token()
TypeError: generate_sas_token() missing 3 required positional arguments: 'uri', 'key', and 'policy_name'
