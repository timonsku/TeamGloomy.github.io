---
title: Sensorless Homing on an SKR Pro v1.1 and v1.2
tags: []
keywords: 
last_updated: 06/01/2023
summary: "Using and Configuring Sensorless Homing on an SKR Pro v1.1 and v1.2"
sidebar: mydoc_sidebar
permalink: skr_pro_sensorless.html
folder: mydoc
comments: false
toc: false
datatable: true
boardname: SKR Pro v1.1 or v1.2
stepperSPI: 2
spiInfo: ""
TMC: "{ PB_10, PE_12, PG_8, PE_15, PE_10, PG_5 }"
example: "stepper.TmcDiagPins = { PB_10, PE_12 }"
example2: "stepper.TmcDiagPins = { NoPin, PE_12 }"
board: biquskrpro_1.1
onboardDrivers: no
GPIO15: PB_12
GPIO13: PB_15
GPIO12: PB_14
GPIO14: PB_13
adapterRXTX: WiFi
---

{% include custom/sensorless.html %}

{% include warning.html content="The SKR Pro v1.1 and v1.2 sensorless homing jumpers don't do anything so if you don't want to use sensorless homing and use normal endstops, you will have to remove the diag pin from your drivers - [Evidence](https://github.com/bigtreetech/BIGTREETECH-GTR-V1.0/issues/12)" %}

{% include custom/sensorless_2.html %}
