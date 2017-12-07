# Real-Time-Temperature-With-LM-35-and-MQTT
Real time temperature monitoring with MQTT and Adafruit IO

Go to https://io.adafruit.com/ and create an account or sign in Go to View AIO Keys and use your Username and Keys to edit Config.h file. In adafruit IO create new feed (under actions). Your feed name must match with the feed name in line 27 of the main code (AdafruitIO_Feed*analog = io.feed("temperature")) . Create a new Dashboard in Adafruit IO. Open the dashboard and add new block by clicking on the "+" sign, choose an appropriate block according to your use. Link the block with your Feed.

The circuit design is simple just connect the output of LM35 -- A0 of NodeMCU, VCC -- 5V and GND -- GND.

Thats it. you can see real time temperature on Adafruit IO dashboard.
