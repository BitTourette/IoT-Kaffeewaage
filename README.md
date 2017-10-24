# IoT-Kaffeewaage
Die Kaffee Maschine der FHWS am SHL nachträglich mit einer 'Füllstandsanzeige' anhand einer Waage unterhalb der Kaffeemaschine erweitern.


### Benötigte Teile:
* [ESP8266/nodeMCU](https://en.wikipedia.org/wiki/NodeMCU)
    * Variante 1  
     http://www.ebay.de/itm/WeMos-D1-WiFi-ESP8266-IoT-im-UNO-Format-NodeMCU-Lua-ESP-12E-DIY-Arduino-IDE-E24-/172436939911?var=&hash=item28260ae487:g:cg8AAOSw-0xYSy7y
    * Variante 2  
     https://www.ebay.de/itm/NodeMcu-Lua-WIFI-Netzwerk-entwicklungs-board-basiert-ESP8266-CP2102-Board-TE390/281892539846?_trkparms=aid%3D555018%26algo%3DPL.SIM%26ao%3D2%26asc%3D46153%26meid%3D38c5c7ce32e24b6ea4abd20b38c03c5b%26pid%3D100005%26rk%3D1%26rkt%3D6%26mehot%3Dag%26sd%3D122751004851&_trksid=p2047675.c100005.m1851
* Wägeelement:  
    * Variante 1  
      https://www.ebay.de/itm/4Stuck-15cm-Bridge-Karosserie-Wagezellenwaage-Elektronische-Wagezelle-50Kg-/351943785939?hash=item51f17bfdd3:g:U3gAAOSwCMFZ5nbo
    * Variante 2  
     https://www.ebay.de/itm/5KG-Bewegliche-Waage-Wiegesensor-Wagezelle-mit-HX711AD-Gewicht-Sensor-Modul-/142311366767?hash=item21226b206f:g:q4cAAOSwWxNYxkyI

* 2 x [HX711AD](https://www.ebay.de/itm/5PCS-Arduino-HX711-Sensor-Dual-Channel-24-Bit-Precision-A-D-Module-TE201-/381273089433?hash=item58c5a5a599:g:kGAAAOSw9eVXVXMF) 
* Lochrasterplatine
* Steckerleiste
* HX711AD [Library](https://github.com/bogde/HX711)
* Gehäuse https://www.ebay.de/itm/Industriegehause-Leergehause-Verteilerkasten-Schaltschrank-Verteilergehause-/191727919905?var=&hash=item2ca3dfe321:g:DNgAAOSwwbdWNJdn
* Netzteil   
    * Variante 1  
    http://www.ebay.de/itm/MeanWell-Netzteile-RS-Serie-Schaltnetzteile-3-3V-5V-12V-15V-24V-48V-/231152362481?var=&hash=item35d1c123f1:g:EVAAAOSwiYFXEe04
    * Variante 2  
    (Steckernetzteil)
* div. Kleinteile
### Dokumentation:





***

### ToDo:

- [ ] Gesammtgewicht ermitteln um die max. Belastung pro Wägeelement zu ermitteln bzw. passendes Wägeelement zu ermitteln.
- [ ] Einbindung in Fachschaftswebsite / Twitter / Benachrichtigung per Push
- [ ] Dokumentation

### Gedanken:

* Ist es evtl sinvoller eine vorhandene Waage zu hacken und die Bauteile zu benutzen (direkte verwendung des vorhandenne (Glas-)Gehäuses)?
* Koffeinkammer zeitgesteuert wieder öffnen nachdem der Kaffee fertig ist?


### Linksammlung:
* [WPA2 Enterprise with ESP8266](https://www.hallgeirholien.no/post/esp8266-eap/)


