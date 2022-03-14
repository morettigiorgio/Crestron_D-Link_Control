# Crestron_D-Link_Control

Modulo per la gestione del Router D-Link DSL-3782 di Infostrada<br/>
Frutta una connessione Telnet con busybox<br/>
https://busybox.net/downloads/BusyBox.html<br/>
<br/>
Note:<br/>
non verifica nessun stato effettivo del modem, manda solo comandi e basta.<br/>
Se si riavvia il modulo il toggle interno della WiFi 2,4GHz ha la memoria e quindi si ricorda lo stato, mentre le altre no.<br/>
Quando il modem ha problemi con internet non risponde più al telnet e quindi il reboot non funziona<br/>
