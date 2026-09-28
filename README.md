# bibliobooks
Applicazione per tutti gli amanti della lettura, indecisi o insicuri su che libro comprare. Permette di scrollare un catalogo di libri e, scegliendo il piano mensile, ricevere a casa un numero di libri segreti, da restituire alla fine del mese. Per evitare di ricevere un libro già letto è permesso creare una lista di lettura inserendo libri già letti e scrivere delle brevi recensioni.


La mia applicazione in breve 
1. un utente per registrarsi inserisce i suoi dati personali
2. nella home sono presenti i libri da visualizzare 
3. un utente loggato può scorrere il catalogo di libri e selezionare quelli che ha già letto
4. il profilo di un libro contiene autore, genere, trama.
5. si crea una lista di libri letti in cui è possibile lasciare una recensione 
6. un utente loggato inserisce i suoi generi preferiti e eventualmente gli autori
7. un utente sceglie il piano che più lo rispecchia (2 libri al mese, 3 libri al mese ecc)
8. l'utente riceve a casa i libri a "sorpresa"
9. alla fine del mese deve restituirli oppure può pagare (il prezzo pieno del libro) e lo tiene
10. se i libri vengono restituiti danneggiati arriverà una multa da pagare in base al tipo di danno
11. se i libri non vengono restituiti in tempo arriveranno delle multe da pagare ogni tot di tempo
12. un utente non loggato può scrollare il catalogo di libri

Funzionalità
- loggare utente
- inserire/modificare/eliminare i libri (admin)
- scorrere il catalogo dei libri disponibili (utente loggato o non loggato)
- lasciare una recensione della lista dei libri già letti (per l'algoritmo dell'app)(utente loggato)
- inserire i propri generi e autori preferiti (utente loggato)
- scelta del piano di ricezione di libri (utente loggato)
- calcolo della scadenza del libro (admin)
- multe in caso di perdita o danneggiamento (segnala come perso, come danneggiato)(admin)

Criteri: (importanza)
- loggare utente
- scelta del piano di ricezione 
- invio dei libri mensilmente
- calcolo scadenza libri
- multe
- inserire le preferenze 
- scorrere il catalogo dei libri
- lasciare una recensione 

Vision: 
- il giorno del compleanno viene regalato un libro 
- Ogni anno che rimani abbonato viene fatto il regalo fedeltà 
- viene inserito qualcosa collaborato con gli autori 
- sconti nelle librerie convenzionate
- disponibilità di libri digitali  
- classifica dei lettori
- brevi video introduttivi per i libri

Requisiti funzionali --> descrivono i servizi, o funzioni, offerti dal
sistema (normalmente attivati da user-input)

Gestione dell'utente
- Il sistema deve permettere a un utente di registrarsi inserendo i propri dati personali.
- Il sistema deve permettere a un utente registrato di effettuare il login.
- Il sistema deve permettere all'utente di modificare i propri dati personali.
- Il sistema deve permettere all'utente di inserire e modificare i propri generi preferiti.
- Il sistema deve permettere all'utente di inserire e modificare i propri autori preferiti.

Catalogo dei libri
- Il sistema deve permettere a un utente, anche non autenticato, di visualizzare il catalogo dei libri disponibili.
- Il sistema deve permettere all'utente di visualizzare le informazioni di un libro.
- Il sistema deve mostrare, per ogni libro, titolo, autore, genere e trama.
- Il sistema deve permettere a un utente loggato di selezionare un libro come già letto.
- Il sistema deve creare e aggiornare la lista dei libri già letti dell'utente.

Recensioni
- Il sistema deve permettere a un utente loggato di lasciare una recensione su un libro già letto.
- Il sistema deve permettere all'utente di visualizzare le proprie recensioni.
- Il sistema deve associare ogni recensione al relativo utente e libro.

Abbonamento
- Il sistema deve permettere all'utente di visualizzare i piani disponibili.
- Il sistema deve permettere all'utente di selezionare un piano di abbonamento.
- Il sistema deve permettere all'utente di modificare il proprio piano.
- Il sistema deve permettere all'utente di visualizzare il proprio piano attivo.

Gestione dei libri da parte dell'admin
- Il sistema deve permettere all'amministratore di inserire nuovi libri.
- Il sistema deve permettere all'amministratore di modificare i dati di un libro.
- Il sistema deve permettere all'amministratore di eliminare un libro.
- Il sistema deve permettere all'amministratore di segnalare un libro come danneggiato.
- Il sistema deve permettere all'amministratore di segnalare un libro come perso/non restituito.
- Il sistema deve permettere all'amministratore di calcolare e registrare la data di scadenza della restituzione.

Spedizione e restituzione
- Il sistema deve permettere di gestire l'invio mensile dei libri agli utenti.
- Il sistema deve permettere all'amministratore di registrare la restituzione dei libri.
- Il sistema deve permettere al sistema di calcolare eventuali multe.
- Il sistema deve permettere all'utente di visualizzare le multe a proprio carico.

Requisiti non funzionali -->  descrivono vincoli sui servizi offerti dal
sistema, e sullo stesso processo di sviluppo
Sicurezza
- Le password degli utenti devono essere memorizzate in forma crittograficamente sicura.
- Il sistema deve impedire agli utenti non autorizzati di accedere ai dati personali degli altri utenti.
- Le funzionalità di amministrazione devono essere accessibili soltanto agli utenti con ruolo amministratore.

Prestazioni
- Il login deve essere completato in meno di 1 secondo in condizioni normali.
- Il catalogo dei libri deve essere visualizzato entro un tempo massimo definito, ad esempio 2 secondi.

Usabilità
- Il sistema deve essere utilizzabile sia da computer sia da dispositivi mobili.
- L'interfaccia deve permettere all'utente di navigare facilmente tra catalogo, libri letti, preferenze e abbonamento.

Disponibilità/affidabilità
- Il sistema deve garantire la disponibilità del servizio per la maggior parte del tempo.
- I dati relativi a utenti, abbonamenti, libri e recensioni devono essere salvati senza perdita di informazioni.


Requisiti di dominio --> (funzionali e non-funzionali) riflettono
caratteristiche generali del dominio applicativo

- Il sistema deve rispettare la normativa vigente in materia di protezione dei dati personali degli utenti, compresi i principi previsti dal GDPR (Regolamento UE 2016/679).
- Il sistema deve raccogliere e trattare i dati personali degli utenti solo per finalità determinate e legittime, fornendo agli utenti le informazioni previste dalla normativa.
- Il sistema deve permettere agli utenti di esercitare i diritti previsti dalla normativa sulla protezione dei dati personali, come accesso, rettifica e, nei casi previsti, cancellazione dei propri dati.
- Il sistema deve adottare misure adeguate per garantire la sicurezza dei dati personali degli utenti.
- Se l'applicazione utilizza pagamenti online, il sistema deve rispettare la normativa applicabile ai servizi di pagamento e alla tutela dei consumatori.
- Il sistema deve fornire all'utente le informazioni relative al contratto di abbonamento, comprese condizioni, prezzo, durata, modalità di rinnovo e recesso, secondo la normativa applicabile ai contratti con i consumatori.
- Le eventuali multe, costi di danneggiamento, mancata restituzione e acquisto dei libri devono essere comunicati all'utente in modo chiaro e devono rispettare la normativa applicabile ai rapporti con i consumatori.
- Se il servizio prevede la raccolta di dati per profilare gli utenti o personalizzare le raccomandazioni, tale trattamento deve rispettare la normativa sulla protezione dei dati personali e gli eventuali obblighi informativi applicabili.
- Se vengono utilizzati cookie o tecnologie di tracciamento, il sistema deve rispettare la normativa applicabile in materia di cookie e strumenti di tracciamento, nel rispetto dell'art. 122 del D.Lgs. 196/2003



