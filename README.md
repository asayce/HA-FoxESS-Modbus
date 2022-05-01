<h2 align="center">
   <a href="https://www.fox-ess.com">FoxESS</a> and<a href="https://www.home-assistant.io"> Home Assistant</a> integration via Modbus RS485
   </br></br>
   <img src="https://github.com/home-assistant/brands/raw/master/custom_integrations/foxess/logo.png" >
   </br>
</h2>


**A community maintained Home Assistant integration using local native polling of data using RS485 over Modbus to enable near realtime data access, with no reliance on the FoxESS cloud portal**

## Supported Hardware
**Hybrid Series** <br>
✅ H1-3.0-E <br>
✅ H1-3.7-E <br>
✅ H1-4.6-E <br>
✅ H1-5.0-E <br>
✅ H1-6.0-E <br>
**AC Series** <br>
✅ AC-3.0-E <br>
✅ AC-3.7-E <br>
✅ AC-4.6-E <br>
✅ AC-5.0-E <br>
✅ AC-6.0-E <br>

We strongly suspect that this plugin will also work with the FoxESS AIO series and 3PH series but have not yet tested. Please let us know if you have an AIO or 3PH system and if the plugin works.

---

⚠️**Requires additional hardware** (RS485 to USB or a WIFI/LAN RS485 converter) & basic electronics competencies required to connect the two additional wires for the RS485 interface to the inverters com connector.⚠️

---

<p>⚠️Warning: The structure and meaning of the data fields has been assumed, not drawn from official documentation. There may be errors - Use this at your own risk.</p>

The aim of this project is to enable the full use of the Energy dashboard in Home Assistant. The current status is most of this is functional, but there are a couple of todos:
* Find register and set up Utility Meter for Grid Consumption
* Find register and set up Utility Meter for Return to Grid

## Manual installation 

* Take a copy / backup of your config and/or HA install before you change it! :)
* Copy the contents of the configuration.yaml file to your config file into the appropriate places
* Put the modbus.yaml file alongside your configuration.yaml file
* Check your config is valid, then Restart HA if so


## Energy Dashboard Configuration

**Electricity Grid**

- Coming Soon

**Solar Panels**

- Select the solar_production__um_daily sensors 

**Home Batteries**

- Select the Battery Dis/Charge Rate sensors

---
## Provided Entities

**Registers**

**The [wiki](https://github.com/StealthChesnut/HA-FoxESS-Modbus/wiki/Data-Register-Reference---H1-AC1) has references for the registers.**

<br>
<br>

> This plugin has been developed as a personal project, with no connection to the official brand of FoxESS, use of this plugin is intended for use by the community without fee but has no warrenty or liablity should any damage, harm or undesired results happen as a result of using this plugin. We strongly recommend that only competently trained individuals attempt to wire the additional connections required for this plugin to function. There is a risk of personal or device damage/harm.
You have been warned!

