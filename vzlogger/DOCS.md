# Home Assistant Community Add-on: vzlogger

## Installation

## Configuration

**Note**: _Remember to restart the add-on when the configuration is changed._

> ⚠️ **Warning:** The configuration of the vzlogger itself cannot be done via the addon configuration. You have to create a configfile inside youre ```share``` directory and point the ```configfile```propertie to this file.<br />
> Please follow see [vzlogger documentation](https://wiki.volkszaehler.org/software/controller/vzlogger/overview_en#configuration) for setting up your vzlogger.

The vzlogger addon has the following config options:

```yaml
configfile: "/share/vzlogger.conf"
```

Here you can define the configfile, taht is used to start vzlogger. 

## Tipps

###  Identify your devices

If you don't know which devices are connected and accessible by vzlogger, take a look in the logfile of your addon. It will write out all tty devices recognized:

```bash
/dev/ttyACM0 - dresden_elektronik_ingenieurtechnik_GmbH_ConBee_II_DE2141675
/dev/ttyUSB0 - Silicon_Labs_CP2104_USB_to_UART_Bridge_Controller_0092C17D
```

### Access your data via Home Assistant

At the moment you have to configure your sensors in Home Assistant manually. You have two options accessing your data:

- Via MQTT (preferred)<br />
  TODO: Write a few lines how to setup the sensors
- Via CMD<br />
  TODO: Write a few lines how to setup the sensors

## Support

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/markussiebert/homeassistant-addon-vzlogger/issues).