#Jupiter Rocket Guidance System git ReadMe

## TO-DO
* Install new Arduino in control system
* Replace LM2596 step-down regulator with fresh unit
* Bring cable gland (likely M20 or M25 for isntalling temp sensor i heater pilot tube
* * SW connected overheat temp sensor in heating element pilot tube. Shuts heater off at
  - setTemp + 5C if in temp reg. mode
  - 103C if in power reg. mode
  

## WISH LIST
* Better 5V source
* Fancy ESP32 controller with better screen and load cells!


## BUG LIST
* The relay control pins maybeeee turns off for a super short time once every period (ssrTempRegPeriod)


## LOG
### 2025-03-18
brew3 flashed to new Ardunio Nano (Arduino-branded!) but *not* installed in control system
