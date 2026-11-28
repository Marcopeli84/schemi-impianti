# Schemi impianti cucine

App web: stanza vuota, mobili disegnabili, import DXF di Metron, simboli e quote. Tutto gira nel browser.

## Pareti
Il numero di pareti non ha limite e le pareti possono avere qualsiasi angolo. Ogni parete è un segmento tra due punti
della pianta, scritto da sinistra a destra guardandolo da dentro la stanza.

Con **Importa DXF** l'app legge per ogni mobile il rettangolo orientato in pianta (angolo compreso), poi raggruppa i lati
dei mobili che guardano nella stessa direzione e stanno alla stessa distanza: ogni gruppo abbastanza lungo è una parete
(una rientranza o un angolo obliquo ne aggiungono una). All'import si apre la pianta interpretata: clicchi sulle pareti che ti servono (diventano verdi), la freccia indica da dove guardi la parete e il pallino ⇄ inverte il lato. All'avvio non c'è nessuna parete scelta; «Mostra pareti suggerite» fa vedere quelle trovate dal programma; «＋ Parete» permette di disegnarne una a mano cliccando due punti, «Nessuna» deseleziona tutto.
Ogni parete ha la sua vista frontale raddrizzata; pianta, soffitto e pavimento mostrano i mobili ruotati e le pareti in verde.

Con **Stanza…** si possono aggiungere, rinominare, nascondere o eliminare pareti (lato fisso oppure «obliqua» con due punti).
I mobili ruotati letti dal DXF si spostano ma non si ridimensionano dai campi numerici.
I file salvati con le versioni precedenti si aprono ancora.

Ogni vista ha in alto i tasti **↔ Specchia** e **↕ Specchia** per rovesciarla da sinistra a destra o dall'alto in basso; simboli e quote seguono la vista e lo specchio viene salvato nel file.

Quando disegni una parete nella pianta dell'import, gli angoli dei mobili sono punti arancioni e il più vicino al cursore si evidenzia con un mirino verde: il clic si aggancia a quel punto.

**Stampa / PDF:** il pulsante «Intestazione stampa…» apre le impostazioni a parte: campi da spuntare e compilare in alto a sinistra (file di origine, nome parete, dettagli tra parentesi, cliente, indirizzo, commessa, data, disegnatore, note e campi propri), logo in basso a destra (`logo.png`, altezza regolabile) e nomi delle pareti. Le scelte restano salvate nel browser per i lavori successivi. Le pareti si rinominano anche con doppio clic sulla scheda.

Ogni campo dell'intestazione, e il logo, ha un menù per scegliere l'angolo del foglio in cui stamparlo (alto/basso, sinistra/destra); nella finestra c'è un'anteprima del foglio.
