# IoT-Kaffeewaage
Die Kaffee Maschine der FHWS am SHL nachträglich mit einer 'Füllstandsanzeige' anhand einer Waage unterhalb der Kaffeemaschine erweitern.


### Benötigte Teile:
* ESP8266/nodeMCU
* Wägeelement:  
    * Variante 1 https://www.ebay.de/itm/4Stuck-15cm-Bridge-Karosserie-Wagezellenwaage-Elektronische-Wagezelle-50Kg-/351943785939?hash=item51f17bfdd3:g:U3gAAOSwCMFZ5nbo
    * Variante 2 https://www.ebay.de/itm/5KG-Bewegliche-Waage-Wiegesensor-Wagezelle-mit-HX711AD-Gewicht-Sensor-Modul-/142311366767?hash=item21226b206f:g:q4cAAOSwWxNYxkyI

* 2 x [HX711AD](https://www.ebay.de/itm/5PCS-Arduino-HX711-Sensor-Dual-Channel-24-Bit-Precision-A-D-Module-TE201-/381273089433?hash=item58c5a5a599:g:kGAAAOSw9eVXVXMF) 
* HX711AD [Library](https://github.com/bogde/HX711)


### ToDo:

- [ ] Gesammtgewicht ermitteln um die max. Belastung pro Wägeelement zu ermitteln bzw. passendes Wägeelement zu ermitteln.

### Gedanken:

* Ist es evtl sinvoller eine vorhandene Waage zu hacken und die Bauteile zu benutzen (direkte verwendung des vorhandenne (Glas-)Gehäuses)?
* Koffeinkammer zeitgesteuert wieder öffnen nachdem der Kaffee fertig ist?


### Linksammlung:
* [WPA2 Enterprise with ESP8266](https://www.hallgeirholien.no/post/esp8266-eap/)
