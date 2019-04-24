# awesome-diy-wx
A collection of resources for diy, semi-professional, 3d-printed and otherwise amazing weather stations.

## Communication

**LOW-COST NVMO CELL NETWORK SERVICE PROVIDERS**

| Provider    | Data-Only Plans | Pay-As-You-Go| Notes |
|-------------|:---------------:|:------------:|-------|
| [RedPocket](https://redpocket.com) | Y | Y | (5/1/2019) ATT 4G LTE - 1GB - $10/mo |


## Qwiic/i2c Sensors

**TEMPERATURE & HUMIDITY**

| Description | Platform | Measurement(s)          | Link(s)   |
|-------------|----------|-------------------------|-----------|
| [Zio Air Pressure Sensor - BMP280]((https://www.smart-prototyping.com/Zio-Qwiic-Air-Pressure-Sensor-BMP280)) | Qwiic / i2C | Temp, Barometric pressure | [Smart-Prototyping.com] |
|  [SparkFun Environmental Combo Breakout - CCS811/BME280]((https://www.sparkfun.com/products/14348)) | Qwiic / i2c | Temp, Humidity, Barometric pressure, eCO2, TVOC | [sparkfun.com] |
 | [Zio Qwiic Temperature Humidity Sensor (SHT31)](https://www.smart-prototyping.com/Zio-Qwiic-Temperature-Humidity-Sensor-SHT31) | Qwiic / i2c | Temp, Humidity | [Smart-Prototyping.com] |
 
**AIR QUALITY**
 
| Description | Platform | Measurement(s)          | Link(s)   |
|-------------|----------|-------------------------|-----------|
| [Zio Qwiic Air Quality Sensor - CCS811](https://www.smart-prototyping.com/Zio-Qwiic-Air-Quality-Sensor-CCS811) | Qwiic / i2C | eCO2, TVOC, Temp | [Smart-Prototyping.com] |
|  [SparkFun Environmental Combo Breakout - CCS811/BME280](https://www.sparkfun.com/products/14348) | Qwiic / i2c | Temp, Humidity, Barometric pressure, eCO2, TVOC | [sparkfun.com] | 
 | [SparkFun Air Quality Breakout - CCS811](https://www.sparkfun.com/products/14193) | Qwiic / i2c | eCO2, TVOC, Temp | [sparkfun.com] |
 

 **AIR PRESSURE**

| Description | Platform | Measurement(s)          | Link(s)   |
|-------------|----------|-------------------------|-----------|
| [Zio Air Pressure Sensor - BMP280](https://www.smart-prototyping.com/Zio-Qwiic-Air-Pressure-Sensor-BMP280) | Qwiic / i2C | Temp, Barometric pressure | [Smart-Prototyping.com] |
 |  [SparkFun Environmental Combo Breakout - CCS811/BME280](https://www.sparkfun.com/products/14348) | Qwiic / i2c | Temp, Humidity, Barometric pressure, eCO2, TVOC | [sparkfun.com] |
 
**SOIL** 

| Description | Platform | Measurement(s)          | Link(s)   |
|-------------|----------|-------------------------|-----------|
| [Zio Qwiic Soil Moisture Sensor](https://www.smart-prototyping.com/Zio-Qwiic-Soil-Moisture-Sensor)| Qwiic / i2C | CO2, VOC, Temp | [Smart-Prototyping.com] |


**PHOTOMETRY / SPECTROMETRY**

| Description | Platform | Measurement(s)          | Link(s)   |
|-------------|----------|-------------------------|-----------|
| [SparkFun Lightning Detector - AS3935](https://www.sparkfun.com/products/15276) | Qwiic / i2C | CO2, VOC, Temp | [sparkfun.com] |
| [SparkFun Particle Sensor Breakout - MAX30105](https://www.sparkfun.com/products/14045) | i2c | photon particle detector | [sparkfun.com] |
| [SparkFun Spectral Sensor Breakout - AS7263 NIR](https://www.sparkfun.com/products/14351) | Qwiic / i2C | 610nm, 680nm, 730nm, 760nm, 810nm, 860nm wavelengths | [sparkfun.com] |
| [SparkFun UV Light Sensor Breakout - VEML6075](https://www.sparkfun.com/products/15089)  | Qwiic / i2c |  UVA (365 ±10nm), and UVB (330 ±10nm) | [sparkfun.com]|
| [ZIO QWIIC LIGHT SENSOR TSL2561](https://www.smart-prototyping.com/Zio-Qwiic-Light-Sensor-TSL2561)  | Qwiic / i2c | visible light, IR and full light (0.1-40K lux) | [Smart-Protoyping.com]|
| [Zio Qwiic RGB Color Sensor TCS34725](https://www.smart-prototyping.com/Zio-Qwiic-RGB-Color-Sensor-TCS34725)  | Qwiic / i2c | RGB color | [Smart-Prototyping.com]|

**MAGNETOMETRY**

| Description | Platform | Measurement(s)          | Link(s)   |
|-------------|----------|-------------------------|-----------|
| [SparkFun Triple Axis Magnetometer Breakout - MLX90393]((https://www.sparkfun.com/products/14571)) | Qwiic / i2C | magnetic fields 0.161µT | [sparkfun.com] |


## 3D Printed Stations and Parts

### Thingiverse
* Thingiverse [full filter for "weather stations"](https://www.thingiverse.com/search?q=weather+station&dwh=305cbdf7ab10d30) - ~200 matches (as of 4/22/2019)

| Description | Detail        | Components| Measurements          | Completeness* |
|-------------|:--------------|-----------|-----------------------|-------------  |
| [LTB Weather Station](https://www.thingiverse.com/thing:2849562) | nice prototype (but complete) station based on arduino Uno; targeted for 9-12 students; includes lesson plan suggestions and activities| wind vane, anemometer, radiation shield | T, P, WS, WD, R      | prototype but all STL files appear to be available |
| [Radiation Shield For Weather Station Temperature/Humidity](https://www.thingiverse.com/thing:1067700)| well designed radiation shield; recommend [Krylon fusion protection](https://www.krylon.com/products/fusion-allinone) for long-term deployments | radiation shield; HTU231D-F (T,H); SHT15 (T, H); AM2315 (T, H); HTM2500LF (H?) | T, H | all STL files appear intact |
| [Solar Powered WiFi Weather Station]() | [Wemos D1](https://wiki.wemos.cc/products:d1:d1_mini_pro) backed solar station for temp/humidity | housing for BMP280, battery and wiring | T, H, P | all files available |
| [Dallas 1 Wire Weather Replacement Parts](https://www.thingiverse.com/thing:364660) | replacement project for D[allas Semiconductor 1-wire](https://tapr.org/kits_t238.html) weather station; _single_ wind speed/direction design | anemometer; wind vane | WS, WD | STL files seem complete for project, but do not include the housing |
| [IoT Weather Station](https://www.thingiverse.com/thing:1985125) | [NodeMCU](https://www.nodemcu.com/) IoT-based temp/humidity/pressure + light sensor; future potential for soil sensor | solar panel, stevenson shield, control box | T, H, L | appears complete; shield is SKP file |
|[eNVIRO sense: outdoor wireless weather station sensor with Stevenson screen]() | radiation shield (Stevenson) with solar power for arduino-based temp/humidity sensors | arduino; temp/humidity | T, H | all STL files seem complete |
| [Simple Wind Speed Sensor / Anemometer 4 Windcups](https://www.thingiverse.com/thing:1773881) | very simple to print anemometer; no electronics | anemometer | WS | no electronics are included, concept design only |