## Hardware

  - Seeed Studio XIAO ESP32C6
  - XKC-Y25-NPN Non-Contact Liquid Level Sensor

## ESPHome instructions

 - Pull project files
 - Install CLI [ESPHome](https://esphome.io/guides/installing_esphome)
 - create a `secrets.yaml` file in the project root with the following contents:
```
wifi_ssid: "YOUR_2.4GHZ_WIFI_SSID"
wifi_password: "YOUR_2.4GHZ_WIFI_SSID_PASSWORD"
home_assistant_key: "HOME_ASSISTANT_API_PRE_SHARED_KEY"
```
 - cd into project folder and run `esphome run config.yaml` to build and upload

## Hardware & Installation

Hardware overview:
![hardware overview](https://raw.githubusercontent.com/aartrost/esphome-sewage-pump-controller/main/pictures/hardware.jpeg)

High voltage box installed:
![High voltage box](https://raw.githubusercontent.com/aartrost/esphome-sewage-pump-controller/main/pictures/high-voltage-box-installed.jpeg)

Completed project:
![High voltage box](https://raw.githubusercontent.com/aartrost/esphome-sewage-pump-controller/main/pictures/final-installation.jpeg)
