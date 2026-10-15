# Montaperti Stagioni

Client Windows del gioco, separato da Montaperti RTS.

[**Scarica il client completo dalla versione più recente**](https://github.com/rigorage/Montaperti-Stagioni-Download/releases/latest)

1. Scarica **Montaperti-Stagioni-Windows-0.4.4.zip** (o la versione successiva).
2. Estrai **tutta** la cartella sul Desktop o in un'altra posizione.
3. Apri **Montaperti Stagioni.exe**. Puoi creare un collegamento a questo file.

Non spostare il solo EXE. Windows 10/11 a 64 bit; Node.js non serve.
Gli archivi **Source code** non contengono il client. **Stagioni-app.zip** è il piccolo pacchetto usato dal programma per aggiornarsi, non il download per la prima installazione.

Il client controlla le nuove versioni all'avvio e ti propone **Aggiorna e gioca** oppure **Gioca senza aggiornare**. Se rimandi, te lo richiede al prossimo avvio. Puoi continuare a usare lo stesso collegamento. Verifica la firma digitale e l'integrità dei pacchetti; se non c'è connessione usa la versione disponibile. Se la nuova versione non si avvia, tenta quella precedente. L'aggiornamento non interrompe le partite.

Per giocare online, una persona crea la stanza e condivide il codice; gli amici scelgono «Entra». Siete **7 partecipanti totali**, con IA nei posti liberi. Hai **30 secondi** per preparativi e privilegi, **15 secondi** per ogni scelta del carosello e **40 secondi** per il mercato. Quando tutti hanno scelto o sono pronti, si avanza subito. Il limite di **20 minuti** parte dal primo carosello, esclusa la lobby: può chiudere la partita prima del ventesimo round se si aspetta sempre la scadenza. L'host deve restare collegato. Il gioco in solitaria funziona offline.

Le preferenze sono in `%APPDATA%\MontapertiStagioni`; gli aggiornamenti in `%LOCALAPPDATA%\MontapertiStagioniUpdater`. Nessun file dell'RTS viene sostituito. Multiplayer verificato con quattro client sullo stesso PC; non ancora provato tra reti differenti. Il client non include un server TURN dedicato.

Il vecchio launcher 0.3.1 installerà ancora automaticamente il primo aggiornamento disponibile; dalla 0.3.2 gli aggiornamenti richiedono conferma.

Questo repository distribuisce il client e i relativi aggiornamenti. La firma dei pacchetti non è un certificato commerciale Windows.
