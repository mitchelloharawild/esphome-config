
<!-- README.md is generated from README.Rmd. Please edit that file -->

# My <img src='esphome.svg' alt='ESPHome' style="height:1.2em;margin-bottom:-0.25em" /> devices

This repository describes IoT devices that I have made or flashed to use
[ESPHome](https://esphome.io/). ESPHome allows you to easily interface
sensors and control outputs using ESP8266/ESP32 microcontrollers for use
with home automation platforms such as [Home
Assistant](https://www.home-assistant.io/). Sensor or output modules
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

Taking control of your own devices can be tricky, so I’m very grateful
to the open source community (especially ESPHome and Home Assistant) for
making this easy!

Here is a table of devices that I use ESPHome with:
