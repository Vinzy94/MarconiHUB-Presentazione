# Marconi HUB

**Una piattaforma digitale modulare progettata per le scuole.**

Marconi HUB riunisce strumenti web per rendere più accessibili le informazioni scolastiche e supportare attività organizzative quotidiane. Il progetto è nato con una prospettiva rivolta alle scuole: non è una piattaforma pensata esclusivamente per un singolo istituto. È attualmente in uso presso l’I.I.S. “G. Marconi” di Torre Annunziata, dove viene sperimentata e sviluppata a partire da esigenze concrete.

Questa pubblicazione presenta il progetto e le sue funzioni senza distribuire il codice sorgente. Le schermate sono state preparate per la presentazione: i nominativi e i contenuti operativi sono stati oscurati o sostituiti con dati dimostrativi.

## Aree funzionali

### Orario Semplice

Consente di consultare l’orario scolastico con prospetti dedicati a classi, docenti, aule, materie e moduli. La vista a griglia organizza le lezioni per giorno e fascia oraria; sono disponibili strumenti per filtrare, colorare e consultare i dettagli dei moduli, oltre a funzioni di stampa ed esportazione in Excel. L’interfaccia è pensata per essere usata sia da postazioni individuali sia su schermi condivisi.

#### Importazione dell’orario: una funzione centrale

Mosaico include un’importazione diretta dei file **`.ofd` in formato XML esportati da Orario Facile**. Il caricamento dell’orario si effettua nell’area Orario Semplice e supporta file fino a 20 MB, un periodo e una settimana per importazione. Le lezioni senza collocazione vengono segnalate e non inserite nella griglia.

> **Compatibilità:** l’importatore attuale riconosce il formato OFD XML di Orario Facile; non è un importatore generico di qualsiasi file `.ofd` o XML. Per orari prodotti con altri software, la disponibilità di un’esportazione XML è un punto di partenza importante: formato e campi vanno verificati e l’eventuale adattamento va concordato con la scuola. Non si presume una compatibilità automatica con tutti i programmi.

La documentazione del produttore di Orario Facile segnala funzionalità di esportazione XML nelle versioni 7 e successive; questo non implica che tutti i formati XML siano intercambiabili. [Orario Facile: aggiornamenti e formati XML](https://www.orariofacile.com/versioniPrecedenti2023/of7-Release.php).

### Orario LIM

Mostra su schermi condivisi un quadro d’insieme dell’attività scolastica: classi, lezione in corso e successiva, materia, aula e fascia oraria. Può essere consultato per plesso o area e aggiornato durante la giornata, così da rendere immediata la lettura delle informazioni nei corridoi e negli spazi comuni. La schermata pubblicata qui ha i contenuti delle lezioni oscurati per tutelare i dati delle persone.

### Mosaico e gestione COE

Mosaico raccoglie strumenti gestionali e organizzativi per il personale autorizzato. Tra le aree presenti vi sono dashboard, gestione docenti, bacheca, documenti, servizi di segreteria/ufficio tecnico e consultazione dell’orario; i moduli effettivamente attivi dipendono dalla configurazione della scuola.

La sezione **COE** aiuta a consultare e organizzare le cattedre con completamento esterno: mette a confronto le ore svolte nell’istituto, quelle presso altre scuole e il totale, con una rappresentazione delle sedi e dei giorni interessati. Sono disponibili viste a schede o elenco e strumenti di stampa ed esportazione. La schermata dimostrativa sostituisce i dati personali e operativi con schede anonime.

### Atrium

Organizza prenotazioni di aule e spazi attraverso viste mensili, settimanali o per elenco. È possibile filtrare per ambiente e stato della prenotazione. L’immagine mostra eventi di esempio, non l’agenda reale dell’istituto.

### Desk

Raccoglie punti di accesso a servizi e richieste interne, come l’assistenza e le attività online rivolte al personale scolastico. Le funzioni possono variare in base alle necessità e alle procedure dell’istituto.

### MiA

È un assistente informativo integrato in alcune pagine della piattaforma. Può aiutare a individuare informazioni selezionate sull’organizzazione e sull’orario. Le risposte dipendono dai dati disponibili e non sostituiscono le comunicazioni ufficiali della scuola.

## Schermate dimostrative

Le schermate illustrano l’interfaccia e alcuni flussi di lavoro. Prima della pubblicazione sono stati oscurati i nominativi dei docenti e sostituiti i dati di prenotazione e le schede COE. Le viste LIM e Orario Semplice mantengono la struttura della consultazione, ma non mostrano l’orario reale.

![Home di Marconi HUB: accesso alle principali aree](immagini/01-home.png)

*Home della piattaforma, attualmente in uso al Marconi.*

![Orario Semplice con dati personali oscurati](immagini/02-orario-semplice.png)

*Prospetto settimanale con nominativi e elenco docenti anonimizzati.*

![Atrium con eventi dimostrativi](immagini/03-atrium.png)

*Agenda mensile per la prenotazione e consultazione degli spazi.*

![Mosaico, sezione COE con schede dimostrative](immagini/04-mosaico-coe.png)

*Vista COE: le schede reali sono state sostituite con contenuti dimostrativi.*

![Assistente informativo MiA](immagini/05-mia.png)

*Esempio dell’assistente informativo integrato.*

![Orario LIM con contenuti anonimizzati](immagini/06-orario-lim.png)

*Schermata progettata per la consultazione rapida su LIM e display condivisi; i dati delle lezioni sono oscurati.*

## Un progetto per le scuole

Marconi HUB nasce per essere discusso e valutato con le scuole interessate. L’esperienza attuale presso l’I.I.S. “G. Marconi” di Torre Annunziata costituisce il contesto d’uso e di sviluppo del progetto, non ne limita la destinazione. Funzioni, configurazione, importazione dei dati e modalità di attivazione possono essere approfondite con ciascun istituto.

Il progetto è ideato e curato da **Vincenzo Rosario Mellone**.

## Collaborazioni

Sono disponibile a confrontarmi con scuole interessate a conoscere Marconi HUB, valutarne l’adattamento o discutere un possibile percorso di attivazione. Ogni collaborazione può partire dalle esigenze dell’istituto e definire insieme ambito, configurazione, dati, infrastruttura, responsabilità e modalità di manutenzione.

Per avviare un confronto: [info@vr-m.it](mailto:info@vr-m.it).

## Codice e condivisione

Questa pubblicazione presenta il progetto senza distribuire il codice sorgente. La disponibilità a collaborare riguarda il confronto, la dimostrazione e la valutazione di possibili percorsi con altre scuole. Eventuali forme di riuso, adattamento o condivisione tecnica saranno concordate separatamente, chiarendo titolarità, autorizzazioni e condizioni di gestione.

## Contatti

- Referente del progetto: Vincenzo Rosario Mellone
- Sito: [vr-m.it](https://www.vr-m.it/)
- Email: [info@vr-m.it](mailto:info@vr-m.it)

---

*Le funzioni e le configurazioni possono evolvere. Per valutare una collaborazione o un’attivazione è necessario un confronto con la scuola interessata.*
