# thing-it-device-art-net

[![NPM](https://nodei.co/npm/thing-it-device-art-net.png)](https://nodei.co/npm/thing-it-device-art-net/)
[![NPM](https://nodei.co/npm-dl/thing-it-device-art-net.png)](https://nodei.co/npm/thing-it-device-art-net/)

[thing-it-node] Device Plugin for Art-Net/DMX 512 universes and lighting (and other equipment) connected to those.

This allows you to 

* control Art-Net universes over the Internet,
* define complex stage designs, storyboards and timer controlled execution 

by means of [thing-it-node](https://github.com/marcgille/thing-it-node) and [thing-it.com](http://www.thing-it.com).

## Installation

After you have 

* [set up](http://www.thing-it.com/thing-it/index.html?document=gettingStarted#/documentationPanel) your [thing-it] Node Box and 
* configured or copied a [thing-it] Mesh with Art-Net Universes, 

connect your Art-Net Universes to your [thing-it] Node Box via Wifi and probably an Art-Net/DMX512 Bridge to connect to 
your DMX devices.

## User Interface

The appearance of the UI of the Art-Net Plugin on the [thing-it] Mobile Client depends on the configured units. 
The <a href="./examples/configuration.js">sample configuration</a> specifies

* 2 RGB Lights
* 1 Simple Light
* 1 Fog Machine
* 1 Moving Head
* a Blackout Service
* 2 Stage Designs (Scene 1 and Scene 2)
* one Storyboard

and would lead to a UI like

<img src="./documentation/images/art-net-universe.png">