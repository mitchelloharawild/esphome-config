
<!-- README.md is generated from README.Rmd. Please edit that file -->

# My <img src='esphome.png' alt='ESPHome'/> devices

This repository describes IoT devices that I have made or flashed to use
[ESPHome](https://esphome.io/). ESPHome allows you to easily interface
sensors and control outputs using ESP8266/ESP32 microcontrollers for use
with home automation platforms such as [Home
Assistant](https://www.home-assistant.io/). Sensor or output components
connected to the microcontroller are described in a YAML configuration
file, which is an abstracts the usual complication of finding and using
good libraries for interfacing them.

Flashing a device with ESPHome provides completely local control of the
device. This is important to me as it provides data privacy, reduces
latency, and avoids reliance on third party providers. Here are some
motivating articles for why cloud connected IoT devices can be a bad
idea:

> ‘\[Google\] are sending an update to each hub to turn your perfectly
> fine home automation hub into a useless piece of plastic.’
>
> [*Home Assistant: Your hub should be local and
> open*](https://www.home-assistant.io/blog/2016/04/05/your-hub-should-be-local-and-open/)

> ‘Owners of Amazon’s own Ring smart doorbells also suddenly found the
> device no longer worked at all.’
>
> [*BBC: Amazon web outage breaks vacuums and
> doorbells*](https://www.bbc.com/news/technology-55087054)

Taking control of commercially available IoT devices can be tricky, so
I’m very grateful to the open source contributors for making this easy!

There are several websites which help describe how to reflash these
devices for local control:

-   ESPHome Devices provides product descriptions and configuration
    files (<https://www.esphome-devices.com/>).
-   Tasmota Supported Devices Repository is a huge list of devices that
    can be reflashed with Tasmota. Tasmota is another popular firmware
    configurator for ESP8266/ESP32 devices. If it can be flashed with
    Tasmota, then you can also use ESPHome. This repository is nice as
    it provides a table of pins for the components in the device
    (<https://templates.blakadder.com/>).
-   The ESPHome cookbook provides recipes for using ESPHome with
    commercial and DIY devices (<https://www.esphome.io/cookbook/>).

Here is a table of devices that I use ESPHome with:
