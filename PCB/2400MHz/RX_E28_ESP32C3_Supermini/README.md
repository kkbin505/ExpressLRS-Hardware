# 2.4G RX ESP32-C3 PCB

## Solder Friendly 2.4GhZ ExpressLRS RX




## Features

* 20x30 footprint
* No SMD components (for easy soldering)
* Components are placed for ease of soldering (easy iron access)
* Use ESP32-C3 Supermini developerment board (LDO, LED already solded)
* 2.4G Lora Module E28
* 5V input (when using the reg), or 3.3V input (bypasses the reg pads) if your FC supplies a decent 3.3V output

## Editing

* The PCB has been developed in EasyEDA, and the custom libraries that were used are attached in the /lib directory. 

## Ordering

* I've had good results using JLCPCB (<https://jlcpcb.com/RAT>). Upload the .zip file in this repo and adjust any PCB parameters that you want (defaults work fine).

## Build

* Build should be self-explanatory soleing ESP32 and E28 in different side of the PCB.

## BOM

* ESP32-C3 Super Mini
* Ebyte E282G4M12S Module

