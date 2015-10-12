# rcSensing

The rcSensing project is focused on using sensative accelerometrs as strong-force seismometers. The intent is to be able to identify events in conflict zones, which can very quite widely. Some of the potential events we intend to detect are.

  - Troop Movements
  - IEDs explosions
  - Heavy weapons (Tanks and Armored Personel Carriers)
  - Artillery Fire

Obviously these are not commen events in Berkeley and so we will first be aproximating strong force via tracking trains. We will be working on detecting the difference between freight and passanger trains and then work on detecting BART trains which should comparatively have a much lighter signature. Once we accomplish this, we plan to experiment with detecting multiple cars on dirt roads which will give us a closer proxy to an event in the field. From there, we would like to start collecting data in the field which we can then analyize but this may be outside the scope of this class.

### Planned Hardware
- Arduino Zero
- BLE Shield or WiFi Shield
- SD Shield
- +- 2g/4g/8g/16g Accelerometer 
- Cell Phone (if using BLE)

### Potential Signal Analysis

- SciKit-Learn + SciPy
- Dato
- MLPy
- PyBrain
- Theono

### Intended Impact
We want this to be a part of a multi-modal system for remote conflict analysis. To be clear, this is to gather more information, not to replace on the group reporting, or other "ground truth" systems but to support them.

[![Join the chat at https://gitter.im/BIDS-collaborative/rcSensing](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/BIDS-collaborative/rcSensing?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Identifying events from audio recordings and other sensors.
