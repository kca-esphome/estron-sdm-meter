# ESTRON Energy Meter data to Wifi <!-- omit in toc -->

Information from modbus RTU energy meter to Wifi by ESPhome.

# Content <!-- omit in toc -->

- [1. Description](#1-description)
- [2. Hardware](#2-hardware)
- [3. Software](#3-software)
  - [3.1. Setup](#31-setup)
  - [3.2. Configuration](#32-configuration)
  - [3.3. Build](#33-build)


# 1. Description

# 2. Hardware

The example hardware is a nodemcuv3 and a RS485 to RS232 converter. 

# 3. Software

This example uses the ESPhome project to receive the measured values from the energy meter.  

## 3.1. Setup

The example device configuration file is *example.yaml*.

## 3.2. Configuration

To set up the WLAN connection, the parameters in *secrets.yaml* must be assigned the correct values. 

## 3.3. 

```bash
foo@bar:~$ docker run [...] -it ghcr.io/esphome/esphome example.yaml compile
```