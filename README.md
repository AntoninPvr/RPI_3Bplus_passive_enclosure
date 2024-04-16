<h1 align="center">
    <img src="https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/logo.png?raw=true" alt="RPI Enclosure Logo" width="200"></a>
    <br>
    Enclosure for Raspberry PI
</h1>

---
![Static Badge](https://img.shields.io/badge/status-active-green)
![GitHub Release](https://img.shields.io/github/v/release/AntoninPvr/RPI_3Bplus_passive_enclosure)
![GitHub License](https://img.shields.io/github/license/AntoninPvr/RPI_3Bplus_passive_enclosure)

This enclosure is designed to be sleek and minimalistic. It is designed to be 3D printed. This case does not provide any camera or display port access. But GPIO are easily accessibles.

<p float="left">
  <img src="https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/render_sd_hdmi.jpg?raw=true"  width="300"/>
  <img src="https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/render_hdmi_usb.jpg?raw=true" width="300" /> 
</p>


## Compatibility
This enclosure support following boards:

* Raspberry PI 1B+
* Raspberry PI 2B
* Raspberry PI 2B 1.2
* Raspberry PI 3B
* Raspberry PI 3B+

## Files

Two versions of the upper part are available. One with GPIO access and one without. Ideal for a clean look or server applications like VPN, DNS...

* `RPI_3bplus_enclosure_lower_1.2.STL` Lower part of the enclosure common to all
* `RPI_3bplus_enclosure_upper_1.2.STL` Orginal upper part of the enclosure with GPIO access
* `RPI_3bplus_enclosure_upper_1.2_no_gpio.STL` Upper part of the enclosure without GPIO access
* `gpio_cover.STL` Cover for GPIO. Best of both worlds, clean look and easy access to GPIO


## Thermal management
This enclosure is designed to be used with passive cooling solution. 35x35x12mm heatsink is recommended.

A 1mm copper plate between the CPU and the heatsink is needed to allow space for surrounding components.

No need for fan event with intense CPU usage.

## Material and print settings
Clearance is 0.2mm for all parts to facilitate assembly. No support is needed.

4x M3x24mm flat-head screws and 4x M3 nuts are needed to assemble the case.

## Run button
1mm hole above jack connector is designed to fit a 6x6mm push button. This button can be used to wake the Raspberry PI.

## Photos

Version 1.0 without clearance for SD card removal

Printing settings:
* 3D printer: Zortrax M200+
* Material: Z-PLA Pro
* Nozzle diameter: 0.4mm
* High quality
* Layer height: 0.09mm
* Infill: 20%
* No support

![gpio](https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/gpio.jpg?raw=true)

![hdmi](https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/hdmi.jpg?raw=true)

Run button hole above jack connector

![isometric](https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/isometric.jpg?raw=true)

![upper_inside](https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/upper_inside.jpg?raw=true)

Little issue with the GPIO border, was to tight. fixed.

![rpi3b](https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/rpi3b.jpg?raw=true)

![rpi3b_heatsink](https://github.com/AntoninPvr/RPI_3Bplus_passive_enclosure/blob/main/img/rpi3b_heatsink.jpg?raw=true)

Kapton tape is used to isolate heatsink from the board.

## Related projects

* #### Raspberry PI 4B Case version is available here:
    > https://github.com/AntoninPvr/RPI4B_Case

    <p align="left">
        <img alt="Screen BAck" src="https://github.com/AntoninPvr/RPI4B_Case/blob/main/img/render_sd_hdmi.jpg?raw=true" width="30%">
    &nbsp;
        <img alt="Screen BAck" src="https://github.com/AntoninPvr/RPI4B_Case/blob/main/img/render_hdmi_usb.jpg?raw=true" width="30%">
    </p>

---

* #### Raspberry PI 5 Case version is available here:
    > https://github.com/AntoninPvr/RPI5_Case

    <p align="left">
        <img alt="Screen BAck" src="https://github.com/AntoninPvr/RPI5_Case/blob/main/img/render_sd_hdmi.jpg?raw=true" width="30%">
    &nbsp;
        <img alt="Screen BAck" src="https://github.com/AntoninPvr/RPI5_Case/blob/main/img/render_hdmi_usb.jpg?raw=true" width="30%">
    </p>
