# Inter-VLAN Routing 

Laboratorio pratico di segmentazione di rete e instradamento tramite approccio Router-on-a-Stick.

## Cosa è stato fatto
* Creazione di due VLAN isolate: VLAN 10 (Marketing: 192.168.10.0/24) e VLAN 20 (Sales: 192.168.20.0/24).
* Configurazione del link Trunk tra lo switch e il Router Core usando l'incapsulamento standard IEEE 802.1Q su sotto-interfacce logiche.
* Risoluzione (Troubleshooting) di un problema iniziale di disallineamento sul cablaggio delle porte fisiche dello switch.

![Topologia di Rete](Immagine%202026-06-25%20225041.png)

## Come funziona (Test di verifica)
La connettività inter-VLAN è convalidata al 100% dal test di ping andato a buon fine tra le due reti differenti, con lo 0% di pacchetti persi e tempi di risposta minimi:

![Verifica Funzionamento](Immagine%202026-06-25%20225333.png)

## Come scaricare ed eseguire il progetto
1. Clicca sul file con estensione `.pkt` presente in questo repository qui sopra.
2. Clicca sul pulsante **Download** (in alto a destra del file) per salvarlo sul computer.
3. Apri il file scaricato direttamente con il software **Cisco Packet Tracer** per testare la simulazione.
