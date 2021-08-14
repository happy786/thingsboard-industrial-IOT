# thingsboard-industrial-IOT
Production monitoring of machine

Hardware required for the projects are following...
1. Raspberry PI
2. Aurdino UNO
3. Jumper wire
4. Relays(24 volt) as industry sensors are 24 volt standards.
5. Two product sensors.

Programming Language required are following
1. Python 3
2. C++

Procedure to be follow
step1: - Install MQTT broker (Paho Mqtt broker download from Eclipse paho website https://www.eclipse.org/paho/index.php?page=clients/python/index.php) on your raspberry PI.

step 2: Create a free registration on thingsboard IOT platform later on if you need you can upgrade to paid version. after that create a device and name it and copy the credential and put it on your raspberry pi python code. 

step 3: - From repository download aurdino code to your Aurdino UNO device by using Aurdino IDE and serial communication.

step 4: Download Python code from repository to your raspberry pi and run using any IDE where python file can be execute.

Now you can see on your thingsboard website under your device latest telemetry data is coming up.

