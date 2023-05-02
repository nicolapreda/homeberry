# homeberry


## Fase iniziale

La fase iniziale di installazione di Raspberry OS Lite su un Raspberry Pi 4 comporta diversi passaggi che possono essere suddivisi in quattro fasi principali:

### Scaricare il sistema operativo

Raspberry OS Lite è disponibile per il download gratuito dal sito ufficiale della Raspberry Pi Foundation. Una volta scaricato il file, è necessario decomprimerlo.

### Flash dell'immagine del sistema operativo

una volta ottenuto il file immagine del sistema operativo, è possibile "flasharlo" sulla scheda SD utilizzata per il Raspberry Pi. Questa operazione può essere eseguita utilizzando strumenti come Raspberry Pi Imager o Etcher.

### Configurazione della rete

Per utilizzare il Raspberry Pi, è necessario configurare la connessione di rete. Questo può essere fatto modificando il file "wpa_supplicant.conf" nella directory di boot della scheda SD, inserendo le informazioni relative alla rete Wi-Fi.

### Collegamento al Raspberry Pi

una volta completate le fasi precedenti, è possibile collegare la scheda SD al Raspberry Pi e accenderlo.

Per quanto riguarda la configurazione di Node-RED tramite SSH, questi sono i passaggi da seguire:

Connessione SSH: dopo aver acceso il Raspberry Pi, è possibile connettersi ad esso tramite SSH utilizzando un client come Putty o il terminale di un sistema operativo Unix.

### Installazione di Node-RED 

Una volta connessi al Raspberry Pi, è possibile installare Node-RED digitando il comando seguente: "sudo apt-get install nodered".

### Configurazione di Node-RED

Dopo l'installazione di Node-RED, è possibile configurarlo digitando il comando "node-red-pi --max-old-space-size=256", che permette di aumentare la quantità di memoria RAM disponibile per Node-RED.

### Accesso a Node-RED 

Dopo la configurazione, è possibile accedere all'interfaccia web di Node-RED digitando l'indirizzo IP del Raspberry Pi seguito dalla porta 1880 (es. http://192.168.0.1:1880) nella barra degli indirizzi del browser web.


