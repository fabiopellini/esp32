# esp32
tools per esp32:telecaricamento etc
usare il servizio web
-aprire CHROME  su https://adafruit.github.io/Adafruit_WebSerial_ESPTool/
-premere il pulsante CONNECT
-selezionare la USB  (es. COM9)

Verrà visualizzato un messaggio tipo:
Chip type ESP32
Connected to ESP32
MAC Address: 50:02:91:8D:72:7C
Uploading stub...
Running stub...
Stub is now running...
Detecting Flash Size
FlashId: 0x1640C8
Flash Manufacturer: c8
Flash Device: 4016
Auto-detected Flash size: 4MB
-Scegliere il File (Pulsante "Chose a file")
-premere PROGRAM
-attendere il termine del caricamento

Scollegare la seriale, premere il pulsante di accensione in OFF, ricollegare la USB e premere il pulsante di accensione in ON, verificare che sulla seriale (tramite terminale PUTTY o altro) compaiano i normali messaagi
del BRIC, o usare la APP Serial Bluetooth Terminal collegandosi tramite BT ed inviare il messaggio I per verificare le Info sul BRIC.
