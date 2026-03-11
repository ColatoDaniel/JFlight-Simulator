# Aeronix
**Aeronix è un videogioco che simula fisiche realistiche di un velivolo, un gioco dedicato a tutti quelli che sono interessati nell'addentrarsi o semplicemente scoprire nuove cose.**

Aeronix sarà disponibile per PC Desktop.

*IDE: NetBeans* <br>
*JDK: 19*


### 28/02/2026
Ci ho messo un po' di tempo ma ho capito che semplicemente dovevo fare un downgrade della versione della piattaforma di Java dalla 25esima alla 19esima, dato che l'esecuzione dell'applicazione test falliva in quanto la versione di Java era troppo nuova rispetto a quella di Gradle.

### 02/03/2026
Ho provato ad importare un modello da internet e impostare una luce così da poterlo illuminare, ma non riesco a vederlo.

### 03/03/2026
Sono riuscito a sistemare, rileggendo il codice ho notato che la scala dell'oggetto dell'auto era veramente troppo piccola, quindi l'ho moltiplicata per 1 milione e adesso è decisamente più grande.

### 07/03/2026
Ho aggiunto un altro paio di modelli .glb all'interno del codice, JME li renderizza bene. Sto prendendo dimestichezza con la creazione/importazione di modelli e l'impostazione della luce e texture