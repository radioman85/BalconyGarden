# Balcony Garden
# About
I want to complete my knowledge of how to get data from an embedded system to the cloud (database, webpage, etc.) and back again. For this I selected my real life problem, i.e. a greenhouse with a single window, that shall be opened and closed (or one may want to control the gate of a chicken house).

However, there are a few new topics in which I have to dig into like
- Cloud side
  - MQTT to communicate inside a TCP network
  - InfluxDB to stor and visualize data (temperature, pressure, humidity)
  - Generating a webpage with visual studio
  - Docker, to gain some simplification when running the different IoT-server-side services (i.e. webpage, MQTT broker and InfluxDB)
- Embedded side
  - Microcontroller (Arduino UNO WiFi board)
  - Temperature Sensor
  - Stepper Motor Shield

# Scope
This is the top level repo of my IoT project. It includes multiple other repositories (as submodules), which then focus on the development of the different topics that are required (web page, docker, firmware, hardware,...). You can gain an overview by the figure below:

![image](https://user-images.githubusercontent.com/25708993/236217307-3450c988-f691-4dff-904d-9a0d6339c63a.png)

# Submodules
- [GreenhouseEmbedded](https://github.com/radioman85/GreenhouseEmbedded) (Firmware and Hardware setup of the embedded part)
- [BalconyGardenWebPage](https://github.com/radioman85/BalconyGardenWebPage) (webpage project, visual studio)
- [BalconyGardenCloudServices](https://github.com/radioman85/BalconyGardenCloudServices) (Setup of MQTT broker, InfluxDB and webpage)

