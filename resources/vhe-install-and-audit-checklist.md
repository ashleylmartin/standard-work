---
description: >-
  This document provides a step-by-step guide for installing Vivint Home
  Essentials (VHE) packages, including thermostats, doorbell cameras, and Wi-Fi
  extenders.
noRobotsIndex: true
icon: file-doc
cover: ../.gitbook/assets/LinkedIn Cover (1).png
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# VHE Install & Audit Checklist

## Introduction

This document provides a step-by-step guide for installing Vivint Home Essentials (VHE) packages, including thermostats, doorbell cameras, and Wi-Fi extenders.

## What is Vivint Home Essentials (VHE)?

Vivint Home Essentials is a standalone program designed to increase customer engagement with smart home technology. The VHE package provides customers with a free system from their energy provider to begin their journey with Vivint.

* This system works independently without Vivint’s professional monitoring services.
* Customers are encouraged to upgrade later for a comprehensive monitored smart home experience.

### What’s in the VHE Package?

The customer’s energy provider supplies the package, which includes:

* SmartHub (1)
* Doorbell Camera Pro (1)
* Element Thermostat (1)
* Chime Extender (1)

***

## Installation Steps

### 1. Tools / Equipment

* Bring in all VHE equipment, tools, and supplies.
* Tools: iPad.
* Equipment: Thermostat, Bridge, Doorbell Camera (DBC), Chime, Wi-Fi Extender.
* Supplies: DBC Wedge, DBC Spacer, V-AC2-A, 6-Way Outlet adapter, Wire, etc.

### 2. Router / Test Thermostat

* Ask customer for router location.
* Plug in Bridge.
* Ask customer for thermostat location.
* Check wire terminal letters for compatibility.
* Verify availability of a Common Wire (C-wire).
* If HVAC is in Cool mode, check for cold air.
* If HVAC is in Heat mode, check for hot air.
  * If heat is not blowing, do not touch the thermostat.
  * If heat is blowing, check condenser fan outside:
    * Fan spinning = Heat Pump.
    * Fan not spinning = Conventional.
* Switch between Cool/Heat to verify system type.

### 3. Doorbell / Chime

* Ask customer for existing doorbell chime location.
* Check RSSI signal outside at the doorbell using Airport Utility.
  * Ensure router SSID is on 2.4 GHz (DBC won’t connect to 5 GHz).
  * If RSSI not between -65 and 0, add a Wi-Fi extender.
* Install and program TP-Link Wi-Fi Extender.
* Run speed test (5 Mbps down / 2.5 Mbps up required).
* Check voltage at doorbell location (must meet 12–24V AC/DC, 10VA, 1.0A).
  * If not, add correct transformer (V-AC2-A or Take Transformer).
* Check for pinched/short wires.
* Install spacers, wedges, or goof plates if needed.
* Remove wires from chime box (use caution—never touch all three).
* Confirm power is off with a voltmeter before removing doorbell.

### 4. Thermostat Installation

* Complete pre-install test:
  * If heating/cooling is not blowing, do not proceed.
  * Confirm Heat Pump vs. Conventional system type.
* Power down furnace/air handler:
  * Turn fan ON (not Auto).
  * Switch off power at HVAC switch or breaker.
  * Confirm power is off (fan stops, thermostat lights out).
* Install thermostat using Therm Flow tool.
* Program thermostat:
  * Confirm wiring.
  * Heat Pump vs. Conventional.
  * Gas vs. Electric.
* Take “before” and “after” photos.
* Test new thermostat (start test with last used mode).

### 5. Doorbell Camera (DBC) Installation

* Return outside while HVAC is running and install DBC.
* If extending wires:
  * Use Dolphin Clips for <18 AWG.
  * Use Wire Nut for 18 AWG.
* Use spacers/wedges/goof plates as needed.
* Connect wires at chime box (Front/Rear + Trans together).
* Complete manual power test:
  * Press and hold DBC button 15 seconds.
  * Release when prompted.
  * Ring lights purple; test result announced.

### 6. App & Device Setup

* Do not use customer’s phone.
* Send app invite via Signals tab.
* Customer creates login and password.

{% tabs %}
{% tab title="Bridge Setup" %}
- Scan QR code on bridge.
- Press pairing button to connect.
{% endtab %}

{% tab title="Thermostat Setup" %}
* Pair device, name it, configure schedule.
* Explain Energy Saving Event screen.
* Configure HVAC settings (humidity, heating type, cooling type, O/B wiring if Heat Pump).
{% endtab %}

{% tab title="DBC Setup" %}
* Pair device, connect to Wi-Fi, complete camera setup.
{% endtab %}

{% tab title="Customer Training" %}
* Walk customer through thermostat and doorbell physical devices.
* Set up Wi-Fi extender if applicable.
{% endtab %}
{% endtabs %}

### 7. Key Points

* Pair devices in final locations.
* Test DBC power on wall (not on jumper).
* Only use one power source for thermostats.
* If C-wire present, remove batteries.
* If no C-wire, install batteries.
* Use Therm Flow as a tool, not just a checklist.

***

## VHE Audit (for Managers)

* Did pro bring in all tools and equipment?
* Did pro plug in Bridge first?
* Did pro check for incompatibilities?
* Did pro test Heat and Cool before powering down?
* Did pro verify system type outside (Heat Pump vs. Conventional)?
* Did pro check RSSI at DBC location?
* Did pro locate transformer and check voltage/labeling?
* Did pro verify voltage with voltmeter?
* Did pro check for pinched wires (add spacer/wedge/goof plate)?
* Did pro remove power at chime box?
* Did pro confirm power off at doorbell?
* Did pro test Heat and Cool after thermostat install?
* Did pro connect wires correctly at chime box?
* Did pro use correct wire connectors?
  * Bean Clip for <18 AWG.
  * Orange Wire Nut for 18 AWG.
* Did pro use correct transformer?
  * Take Transformer (<18 AWG).
  * V-AC (18 AWG).
* Did pro complete DBC power test?
* Did customer complete onboarding steps?
* Did customer log into app and set up devices?
* Did pro train customer on thermostat, doorbell, and chime?
* Did pro clean up and leave equipment with homeowner?



{% hint style="warning" %}
Review the [hvac.md](hvac.md "mention") for in-depth guidance for installing thermostats and handling HVAC systems correctly.
{% endhint %}
