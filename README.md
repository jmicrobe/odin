# ODIn (Optical Density Investigation)

Repo for documentation related to the Optical Density Instrument at the Stahl lab

## Download repository

After setting up [ssh keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) connected to your github account from command line, run the following command

`git clone git@github.com:jmicrobe/odin.git`

## Introduction

A method of measuring microbial growth is done by measuring the change of turbity over time. This device is designed to take continuous measurements of turbity using and infrared feedback loop as the cultures are being shaken on a platform inside 64 pressurized batch culture growth vessels. The optical density will automatically get sent to a database to be easily accessed for observation.

## Apparatus Environment Implecations
> Ex: necessary temperature to operate. LEDs, phototransistor, microprocessing etc

## Setup Arduino

> TODO need to make sure this is the right model

This project is designed with the [Arduino Mega 2560](https://store.arduino.cc/arduino-mega-2560-rev3)

### Shields

#### Data Logger

> TODO describe more about data logger specifically how it is used in project. issue #10

Logs data to be prepared to be uploaded to the database. [Data Logger from Adafruit](https://www.adafruit.com/product/1141?gclid=EAIaIQobChMImqmPr9Hv1wIVE2t-Ch1ZOwSYEAAYASAAEgI-BPD_BwE)

#### Ethernet

> TODO more information of how and where data is uploaded. issue #11

Sends data to the database. [Ethernet Shield](https://store.arduino.cc/arduino-ethernet-shield-2)

### Libraries

> TODO look at code, try to aggregate libraries issue #7

## Circuits

### Express PCB

> TODO find out how to do this. Issue #1

### Resitor selections

> TODO this appeared to be described in the original docs, so here's a placeholder

## Bill of Materials

> TODO issue #9

## References

> TODO need to gather any information that helped with the creation of the project

## Credits

> TODO Get every name that deserves love!

