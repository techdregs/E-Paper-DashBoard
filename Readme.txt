Youtube Video: 
https://youtu.be/qJuF58CjwIA

Hardware used was a Adafruit Feather V1 ESP32 and a Waveshare 7.5" epaper screen.

Instructions: 

1. Create file in /config for forecasts.yaml. Add "template: !include Forecasts.yaml" to configuration.yaml. Restart Home Assistant.

2. Create device in ESPHome using epaper-dashboard.yaml. Modify as desired.

-----

I was inspired by seeing Madelena's project: 
https://community.home-assistant.io/t/use-esphome-with-e-ink-displays-to-blend-in-with-your-home-decor/435428
https://github.com/Madelena/esphome-weatherman-dashboard

MDI TFT file: 
https://community.home-assistant.io/t/display-materialdesign-icons-on-esphome-attached-to-screen/199790/16