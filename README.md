# Arduino-ESP8266-ChronoDelta-WebServer
This is a web server meant to be build and push to an arduino to mesure time alapsed between to events on two different GPIO pin  

Final objective is to train moto driving skills  
Two laser gates are place on a strait track an the driver must spend more than 12 second to cross between the gates

Feedback is directly provided through a GPIO but also through a web page

The ESP will distribute the Page and Provide a API to query the latest result

The page store the history but the ESP Flush result everytime it is sent to save memory.
