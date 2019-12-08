# openhab-evcharger
OpenHAB Rules to manage Electric Vehicle Charging. 

Charging modes: 
- Manual
- Photovoltaic 
- Scheduled

Hardware used:
- 2 KEBA KeContact P30 Wallboxes
- Fronius Symo Inverter with Fronius Datamanager
- Fronius Smartmeter
- Fronius Ohmpilot
- Tesla Model S (3-phase current)
- Renault Zoe (3-phase current, won't charge lower than 12A)

Smarthome System:
OpenHAB 2.4
https://www.openhab.org/

Keba Binding: 2.5.0-SNAPSHOT
https://github.com/openhab/openhab2-addons/blob/09f0c8d53b00d185ba10d16a584e7cf5cba73b76/bundles/org.openhab.binding.keba/README.md 
