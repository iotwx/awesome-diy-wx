# awesome-diy-wx
A collection of resources for diy, semi-professional, 3d-printed and otherwise amazing weather stations.

<!-- TOC depthFrom:2 depthTo:2 withLinks:1 updateOnSave:1 orderedList:0 -->

- [IoT device management](#iot-device-management)
- [Communication](#communication)
- [Qwiic/i2c Sensors](#qwiici2c-sensors)
- [3D Printed Stations and Parts](#3d-printed-stations-and-parts)
- [Sensor Tests and Experiments](#sensor-tests-and-experiments)

<!-- /TOC -->

## IoT device and data management 

**OPEN SOURCE DATA MANAGEMENT PLATFORMS**
* [CHORDS](http://chordsrt.com); open source data platform for real-time visualization, dashboards and APIs

**OPEN SOURCE MANAGEMENT PLATFORMS**
* [Blynk](https://blynk.io/); cloud platform for device management, configuration, monitoring and analytics.  The **open-source** server is here: [https://github.com/blynkkk/blynk-server](https://github.com/blynkkk/blynk-server) 
* [KaaIoT](https://www.kaaproject.org/); cloud platform for device management, configuration, monitoring and analytics 
* [SiteWhere](http://www.sitewhere.org/); MongoDB and Grafana integration
* [ThingSpeak](https://thingspeak.com/); IoT data analysis platform with MATLAB integration
* [DeviceHive](https://devicehive.com)
* [Zetta](https://zettajs.org)
* [Thingsboard.io](https://thingsboard.io); data collection, processing visualization and device management
* [Thinger.io](https://thinger.io)
* [MainFlux](https://mainflux.com)
* [THiNX](https://thinx.cloud); simplified, streamlined development, deployment and updating from git repositories supporting (among many others) ESP32, ESP8266, Arduino, Onion, Raspberry Pi and PC platforms  


See more at [H2S Media: 9 Best & Top Open source IoT Platforms To Develop the IOT Projects /H2S Media Team / 04-13-2019](https://www.how2shout.com/tools/best-opensource-iot-platforms-develop-iot-projects.html) and [The Top Open Source IoT Platforms for Developers / Dr. Anand Nayyar / 10-23-2018](https://opensourceforu.com/2018/10/the-top-open-source-iot-platforms-for-developers/).

**ARCHITECTURE AND PLANNING**
* [IoT Project Planning / Best Practices by Viki Zabala / 03-26-2018](https://www.iotone.com/guide/iot-project-planning-best-practices/g1070); a nice high-level view of project planning for IoT deployments.

**CONFIGURATION MANAGEMENT**
* [Ansible](https://www.ansible.com/overview/it-automation); Ansible is a simple automation language for describing an applications IT infrastructure.

## Communication

**LOW-COST MVNO (Mobile Virtual Network Operator) CELL NETWORK SERVICE PROVIDERS**

| Provider    | Data-Only Plans | Pay-As-You-Go| Notes |
|-------------|:---------------:|:------------:|-------|
| [RedPocket](https://redpocket.com) | Y | Y | (5/1/2019) ATT 4G LTE - 1GB - $10/mo |


## Qwiic/i2c Sensors

**TEMPERATURE & HUMIDITY**

| Description | Measurement(s)          |  Project link(s)   |
|-------------|-------------------------|-----------|
| [Zio Air Pressure Sensor - BMP280](https://www.smart-prototyping.com/Zio-Qwiic-Air-Pressure-Sensor-BMP280) |   Temp, Barometric pressure | [Smart-Prototyping.com] |
|  [SparkFun Environmental Combo Breakout - CCS811/BME280](https://www.sparkfun.com/products/14348) |   Temp, Humidity, Barometric pressure, eCO2, TVOC | [sparkfun.com] |
 | [Zio Qwiic Temperature Humidity Sensor (SHT31)](https://www.smart-prototyping.com/Zio-Qwiic-Temperature-Humidity-Sensor-SHT31) |   Temp, Humidity | [Smart-Prototyping.com] |

**AIR QUALITY**

| Description | Measurement(s)          |  Project link(s)   |
|-------------|-------------------------|-----------|
| [Zio Qwiic Air Quality Sensor - CCS811](https://www.smart-prototyping.com/Zio-Qwiic-Air-Quality-Sensor-CCS811) |   eCO2, TVOC, Temp | [Smart-Prototyping.com] |
|  [SparkFun Environmental Combo Breakout - CCS811/BME280](https://www.sparkfun.com/products/14348) |   Temp, Humidity, Barometric pressure, eCO2, TVOC | [sparkfun.com] |
 | [SparkFun Air Quality Breakout - CCS811](https://www.sparkfun.com/products/14193) |   eCO2, TVOC, Temp | [sparkfun.com] |


 **AIR PRESSURE**

| Description | Measurement(s)          |  Project link(s)   |
|-------------|-------------------------|-----------|
| [Zio Air Pressure Sensor - BMP280](https://www.smart-prototyping.com/Zio-Qwiic-Air-Pressure-Sensor-BMP280) |   Temp, Barometric pressure | [Smart-Prototyping.com] |
 |  [SparkFun Environmental Combo Breakout - CCS811/BME280](https://www.sparkfun.com/products/14348) |   Temp, Humidity, Barometric pressure, eCO2, TVOC | [sparkfun.com] |

**SOIL**

| Description | Measurement(s)          |  Project link(s)   |
|-------------|-------------------------|-----------|
| [Zio Qwiic Soil Moisture Sensor](https://www.smart-prototyping.com/Zio-Qwiic-Soil-Moisture-Sensor)|   CO2, VOC, Temp | [Smart-Prototyping.com] |


**PHOTOMETRY / SPECTROMETRY**

| Description | Measurement(s)          |  Project link(s)   |
|-------------|-------------------------|-----------|
| [SparkFun Lightning Detector - AS3935](https://www.sparkfun.com/products/15276) |   lightning | [sparkfun.com] |
| [SparkFun Particle Sensor Breakout - MAX30105](https://www.sparkfun.com/products/14045) | photon particle detector | [sparkfun.com] |
| [SparkFun Spectral Sensor Breakout - AS7263 NIR](https://www.sparkfun.com/products/14351) |   610nm, 680nm, 730nm, 760nm, 810nm, 860nm wavelengths | [sparkfun.com] |
| [SparkFun UV Light Sensor Breakout - VEML6075](https://www.sparkfun.com/products/15089)  |    UVA (365 ±10nm), and UVB (330 ±10nm) | [sparkfun.com]|
| [ZIO QWIIC LIGHT SENSOR TSL2561](https://www.smart-prototyping.com/Zio-Qwiic-Light-Sensor-TSL2561)  |   visible light, IR and full light (0.1-40K lux) | [Smart-Protoyping.com]|
| [Zio Qwiic RGB Color Sensor TCS34725](https://www.smart-prototyping.com/Zio-Qwiic-RGB-Color-Sensor-TCS34725)  |   RGB color | [Smart-Prototyping.com]|

**MAGNETOMETRY**

| Description | Measurement(s)          | Project link(s)   |
|-------------|-------------------------|-----------|
| [SparkFun Triple Axis Magnetometer Breakout - MLX90393](https://www.sparkfun.com/products/14571) |   magnetic fields to 0.161µT | [sparkfun.com] |


## 3D Printed Stations and Parts


### UCAR/NCAR
| Description | Detail        | Components| Measurements          | Completeness* |
|-------------|:--------------|-----------|-----------------------|-------------  |
| [3DPAWS 3D Printed Automatic Weather Station](https://sites.google.com/ucar.edu/3dpaws/) | complete weather  station based on Raspberry Pi B; targeted for amateur and professional use; developed at [UCAR COMET](https://comet.ucar.edu)  | wind vane, anemometer, radiation shield | T, P, H, WS, WD, R      | prototype with extensive build manual (>300pp); STL files are available online |

[This article about FabCafe Bangkok's FARM HACK 2.0](http://www.progressth.org/2016/12/3d-printed-iot-weather-station.html) describes the station prototype based on NodeMCU (see all IoT Weather Station below) demonstrating the importance and impact 3D printing may have on weather sensing technologies, especially in areas that may not have as many resource for commercial solutions.

### Thingiverse
* Thingiverse [full filter for "weather stations"](https://www.thingiverse.com/search?q=weather+station&dwh=305cbdf7ab10d30) - ~200 matches (as of 4-22-2019)

| Description | Detail        | Components| Measurements          | Completeness* |
|-------------|:--------------|-----------|-----------------------|-------------  |
| [LTB Weather Station](https://www.thingiverse.com/thing:2849562) | nice prototype (but complete) station based on arduino Uno; targeted for 9-12 students; includes lesson plan suggestions and activities| wind vane, anemometer, radiation shield | T, P, WS, WD, R      | prototype but all STL files appear to be available |
| [Radiation Shield For Weather Station Temperature/Humidity](https://www.thingiverse.com/thing:1067700)| well designed radiation shield; recommend [Krylon fusion protection](https://www.krylon.com/products/fusion-allinone) for long-term deployments | radiation shield; HTU231D-F (T,H); SHT15 (T, H); AM2315 (T, H); HTM2500LF (H?) | T, H | all STL files appear intact |
| [Solar Powered WiFi Weather Station]() | [Wemos D1](https://wiki.wemos.cc/products:d1:d1_mini_pro) backed solar station for temp/humidity | housing for BMP280, battery and wiring | T, H, P | all files available |
| [Dallas 1 Wire Weather Replacement Parts](https://www.thingiverse.com/thing:364660) | replacement project for D[allas Semiconductor 1-wire](https://tapr.org/kits_t238.html) weather station; _single_ wind speed/direction design | anemometer; wind vane | WS, WD | STL files seem complete for project, but do not include the housing |
| [IoT Weather Station](https://www.thingiverse.com/thing:1985125) | [NodeMCU](https://www.nodemcu.com/) IoT-based temp/humidity/pressure + light sensor; future potential for soil sensor | solar panel, stevenson shield, control box | T, H, L | appears complete; shield is SKP file |
|[eNVIRO sense: outdoor wireless weather station sensor with Stevenson screen]() | radiation shield (Stevenson) with solar power for arduino-based temp/humidity sensors | arduino; temp/humidity | T, H | all STL files seem complete |
| [Simple Wind Speed Sensor / Anemometer 4 Windcups](https://www.thingiverse.com/thing:1773881) | very simple to print anemometer; no electronics | anemometer | WS | no electronics are included, concept design only |


## Sensor Tests and Experiments

* [Battery Powered ESP8266](https://homecircuits.eu/blog/battery-powered-esp8266-iot-logger/)
* [Feather Huzzah Realistic Power Consumption](http://hex.ro/wp/blog/feather-huzzah-esp8266-realistic-power-consumption/)
