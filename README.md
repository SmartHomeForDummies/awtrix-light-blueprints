# Awtrix Fenster Status bei Regen.
Zeigt die Anzahl und oder die Namen der offener Fenster auf der Awtrix/Ulanzi an.
Die App wird aktiviert sobald es beginnt zu regnen und mindestens 1 Fenster geöffnet ist.
Oder Während es bereits regnet und mindestens ein Fenster geöffnet wird. Beendet wir die App,
wenn es entweder aufhört zu regnen oder alle Fenster geschlossen werden während es noch regnet.
  # Voraussetzungen:
  - Custom Firmware Awtrix Light https://blueforcer.github.io/awtrix-light/#/
  - Fenster Gruppe: Eine binary_sensor Gruppe wurde erstellt, welche alle zu überwachende Fenster beinhaltet.
  - Regen Sensor: Ein Regen Sensor (binary_sensor), sollte keiner zur Verfügung stehnen, könnt ihr euch auf Basis
  einen Reggenmengen Sensors oder des Wetter Sensore einen Template Sensor erstellen.
  - Das verwendete ICON mit der Icon ID: 1819 findet verwendung. Diese herunterladen und in water.gif umbennenen.



![Alt text](/images/Awtrix-Fenster%20Status%20bei%20Regen.gif?raw=true "Awtrix Fenster Status bei Regen")

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2Fawtrix-light-blueprints%2Fblob%2Fmain%2Fawtrix_fenster_status_bei_regen.yaml)

-------

# Awtrix Benachrichtigung.
Zeigt eine belibiege Benachrichtigung und ein Icon auf der Awtrix/Ulanzi an.
Die Vorgabe der Benachrichtigung erfolgt über einen Input Text Helfer.
Die Vorgabe des Icons erfolgt über einen Input Select Helfer.

  # Voraussetzungen:
  - Custom Firmware Awtrix Light https://blueforcer.github.io/awtrix-light/#/
  - Input Text: Für die Text Benachrichtigung
  - Input Select: Für die Icon Auswahl. Auswahl an verfügbaren Icons als Auswahlliste
  - Input Boolean: Zum Ein-und Auschalten der App


[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FSmartHomeForDummies%2Fawtrix-light-blueprints%2Fblob%2Fmain%2Fawtrix_benachrichtigung.yaml)

-------
[![Donate with PayPal](https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-200px.png)
](https://community.smarthome-for-dummies.de/donate)


