# lightyfi

lightyfi ist der Entwurf einer, auf open-source software sowie hardware basierten, Lichtfliese mit WLAN-Anbindung und Steuerung per Android-App

# Aufbau der Ordner
Die Ordner im git sind gegliedert und gleichzeitig etwas Durchmischt.
Das root-Verzeichnis enthält alle Übergeordneten Daten, ansonsten sind Unterverzeichnisse angelegt.
Das Projekt entsteht aus einer Bastelidee mit dem LoLin NodeMcu v3, weshalb unter "src" der Quelltext hierfür abgelegt ist.

-app      | Ordnerinhalt sind platformspezifische Unterordner 
--android | Ordnerinhalt ist die Android-App
-lib      | Automatischer, von PlatformIO generierter, Ordner
-pcb      | Enthält den Schaltplan sowie die Platinenlayouts der lightyfi Hauptplatine
-src      | Enthält den Programmcode für den ESP8266 Controller


# Verwendete Software
Zum Einsatz kommt in der Projekterstellung folgende Software:
- GitKraken, als git-client
- Atom mit PlatformIO
- KiCad

Alle libraries werden, sofern möglich, zusammen mit dem Projekt hier im git gepusht.



----- Der Inhalt ist noch absolut Roh und nahezu unbenutzbar -----
