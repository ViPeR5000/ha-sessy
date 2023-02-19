# ha-sessy
Home Assistant integration for Sessy home battery system.
Work in progress :)

Currently supported:
- Connect to Battery or P1 Dongle
- Power Status sensors
- Wifi RSSI sensor (Battery only)
- P1 Status sensors (P1 Dongle only)

TODO:
- [X] Add Power Status sensors
- [ ] Add Power Strategy sensors
- [ ] Add Power Setpoint service
- [ ] Add Power Strategy service
- [ ] Add Energy sensors
- [ ] Add update entities
- [X] Add Device Registry information
- [ ] Add logo to home-assistant/brands
- [ ] Add HACS configuration

Installation
============

HACS
----
Add this repository to HACS via the Custom Repositories options

Manual
------
- Copy the `custom_components/sessy` folder to the `custom_components` folder in your configuration directory.

Configuration
=============
Add Sessy via the Integrations menu: 

- Go to Integrations > Add Integrations > Sessy

  [![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=sessy)

- Enter the IP address or hostname and the local username and password for the device you want to add

- The integration will discover the device type and add it to Home Assistant

