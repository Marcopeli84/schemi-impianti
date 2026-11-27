# Schemi impianti cucine

App web: stanza vuota, mobili disegnabili, import DXF di Metron, simboli e quote. Tutto gira nel browser.

## Pareti
Il numero di pareti non ha limite e le pareti possono avere qualsiasi angolo. Ogni parete è un segmento tra due punti
della pianta, scritto da sinistra a destra guardandolo da dentro la stanza.

Con **Importa DXF** l'app legge per ogni mobile il rettangolo orientato in pianta (angolo compreso), poi raggruppa i lati
dei mobili che guardano nella stessa direzione e stanno alla stessa distanza: ogni gruppo abbastanza lungo è una parete
(una rientranza o un angolo obliquo ne aggiungono una). Le pareti trovate si spuntano nella finestra di import.
Ogni parete ha la sua vista frontale raddrizzata; pianta, soffitto e pavimento mostrano i mobili ruotati e le pareti in verde.

Con **Stanza…** si possono aggiungere, rinominare, nascondere o eliminare pareti (lato fisso oppure «obliqua» con due punti).
I mobili ruotati letti dal DXF si spostano ma non si ridimensionano dai campi numerici.
I file salvati con le versioni precedenti si aprono ancora.
