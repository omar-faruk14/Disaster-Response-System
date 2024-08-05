# Disaster Response System

## Overview
This project is designed to develop and implement a disaster response system that leverages drone-collected BLE device RSSI values and geographic coordinates. The system is capable of generating and loading KMZ files onto maps for efficient visualization. The primary technologies used include React.js, Node.js, Leaflet, and Japan GSI map tiles.

## Hardware Description
### Drone and BLE Device
- **Drone**: A drone with a payload capacity of at least 1 kg, capable of carrying the EMI-01s unit.


## Software Features

![Project Image](/img/Heatmap.png)

### Data Collection
- **BLE Device RSSI Values**: Collects RSSI values from BLE devices to determine the proximity and location of potential rescuees.
- **Geographic Coordinates**: Captures and records the geographic coordinates using the drone's GPS system.

### Data Visualization
- **Heatmap Creation**: Generates heatmaps based on the RSSI values and geographic coordinates. Areas with stronger signals are displayed with more intense colors, while weaker signals are shown with less intensity.
- **GeoJSON Mesh Grid**: Creates a mesh grid with 10m x 10m resolution to accurately represent spatial data. This grid helps in pinpointing the exact locations of rescuees.
- **KMZ File Generation**: Produces KMZ files that can be loaded onto maps for a 3D view within OpenStreetMap. This feature allows for a comprehensive visualization of the disaster area.
- **Map Integration**: Utilizes Leaflet and Japan GSI map tiles to seamlessly integrate spatial data into maps, providing an accurate representation of the affected area.

### Application Use
- **Rescue Operations**: Facilitates swift and efficient rescue operations by providing real-time location data of potential rescuees.
- **Remote Information Sharing**: Enables remote sharing of location data and heatmaps, allowing rescue teams to coordinate efforts effectively.

## Project Motivation
The primary goal of this project is to enhance disaster response capabilities by leveraging modern IT technologies. By quickly identifying and locating individuals in need of rescue, the system aims to save lives and improve the efficiency of rescue operations. The project draws inspiration from past disasters, emphasizing the importance of timely and accurate rescue efforts.


