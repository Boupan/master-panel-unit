# master-panel-unit
What started to be a boiler ON/OFF circuit is now a power measurement and weather notifier station

Features:

* Power measurement through an SCT-013-000 current transformer wrapped around the mains cable
* Boiler ON/OFF circuitry through a secondary logic-level relay and a primary high voltage "power relay" installation 
* Weather status from an outside station plus info for future and current weather data parsed through an API
* Android app for WiFi control and monitoring
* Nextion touch screen to give the visual
* OTA programming since we do not want any hands-on approach after installation

Hardware:

Power Relay (240V-240V) AC
Transformer 240VAC -> 5VDC 2A
Relay module 5V drived
NodeMcu OR arduino pro mini+ ESP-01S
Nextion 2.4' touch screen
Casing for Din rail
Compatible high-voltage high-current  cables


----------------------------------------------------------------------------------------------

1) We have to test the circuit near high voltage cables while we draw significant amount of power 
plus during switching ON and OFF some loads and monitor its behaviour during the current spikes

2) Installation is proposed to be done by an official electrician due to local-laws and policies

3)Fail-safe hardware circuitry + circuit breaker before the circuit
