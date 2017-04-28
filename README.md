# Touch-xCH
How to use in home-assistant?

You can add the following sensor topic in your configuration.yaml

switch:

- platform: mqtt

  name: "Touch Light1"
  
  state_topic: "stat/switch/POWER1"
  
  command_topic: "cmnd/switch/power1"
  
  qos: 1
  
  payload_on: "ON"
  
  payload_off: "OFF"
  
  retain: true
  
- platform: mqtt

  name: "Touch Light2"
  
  state_topic: "stat/switch/POWER2"
  
  command_topic: "cmnd/switch/power2"
  
  qos: 1
  
  payload_on: "ON"
  
  payload_off: "OFF"
  
  retain: true

Support the following device:

  TOUCH_1CH
  
  TOUCH_2CH
  
  TOUCH_3CH
  
  TOUCH_4CH
  
  ![image](https://github.com/ItownTech/Touch-xCH/blob/master/image/touch_4ch.png)
