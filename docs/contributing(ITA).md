# Contributing to LibreWings
Grazie per il tuo interesse in LibreWings!
LibreWings è un progetto open source sviluppato con Godot 4.5, pensato per crescere nel tempo grazie alla collaborazione della community.
Che tu sia:
-programmatore
-artista 3D
-sound designer
-tester
-o semplicemente pieno di idee

sei il benvenuto.
Questa guida spiega come contribuire correttamente, passo dopo passo.

## Filosofia del progetto
LibreWings punta a essere:
-open source
-educativo
-divertente
-collaborativo
-tecnicamente pulito

Non cerchiamo la perfezione assoluta, ma:
codice chiaro, idee sensate e miglioramenti concreti

## A cosa puoi contribuire
Puoi contribuire in molti modi, qui in seguito ne trovi elencati alcuni:

## Codice
-sistemi di volo
-armi e radar
-HUD
-AI
-ottimizzazione
-bugfix

## Asset open source
-modelli 3D originali
-texture open
-suoni open
-icone

Tutti gli asset devono essere:
-creati da te
-oppure sotto licenza compatibile con GPLv3

## Documentazione
-migliorare il README
-aggiungere tutorial
-spiegare sistemi complessi
-traduzioni

## Testing
-segnalare bug
-suggerire miglioramenti
-testare nuove feature

## Prima di iniziare
-Controlla le Issue aperte
-Leggi la Roadmap
-Verifica che la feature non sia già in sviluppo
-Se hai dubbi → apri un’Issue prima di iniziare
-Questo evita lavoro doppio e caos inutile

## Workflow consigliato (passo per passo)
1️. Fork del repository

-Vai sulla pagina GitHub di LibreWings
-Clicca Fork
-Otterrai una copia del progetto sul tuo account

2️. Clona il tuo fork sul PC

git clone https://github.com/TUO_USERNAME/LibreWings.git

Oppure usa GitHub Desktop:
-File → Clone repository
-Seleziona il tuo fork

3️. Crea un branch per la tua feature

-Non lavorare mai direttamente su main.
-Nome consigliato:
feature/radar-system oppure fix/hud-bug oppure docs/improve-contributing ecc.

usa il comando: 
git checkout -b feature/nome-feature

4️. Lavora sul progetto

-Usa Godot 4.5
-Mantieni il codice leggibile
-Commenta le parti complesse
-Segui lo stile esistente

## Struttura consigliata:
-codice → engine/
-scene → godot_project/scenes/
-script → godot_project/scripts/
-asset open → assets_open/

5️. Commit chiari e descrittivi

Messaggi di commit semplici e onesti:

✅ Buoni esempi:
-Added basic radar tracking system
-Fixed missile lock bug
-Improved HUD readability

❌ Da evitare:
-update
-stuff
-changes

6️. Push e Pull Request

git push origin feature/nome-feature

Poi su GitHub:
-apri una Pull Request
-descrivi cosa hai fatto
-spiega perché è utile

## Revisione delle Pull Request
Tutte le PR vengono:
-lette
-testate
-commentate

Possibili esiti:

✅ Merge

🛠 Richiesta modifiche

❌ Rifiuto (con spiegazione)

Rifiutare una PR non è personale, serve a mantenere qualità e coerenza.

## Regole importanti
Licenza:

LibreWings usa GPLv3.
Contribuendo accetti che:
-il tuo codice resti open source
-le modifiche rimangano sotto GPLv3

Cosa NON è accettato:
-codice copiato da progetti closed source
-asset rubati o non tuoi
-cheat, malware, backdoor
-comportamenti tossici o aggressivi

Codice di comportamento:
Sii:
-rispettoso
-collaborativo
-costruttivo

Non servono geni arroganti.
Servono persone curiose che vogliono costruire qualcosa insieme.

## Consiglio finale
Non serve fare contributi enormi.
Anche:
-una riga di documentazione
-un fix piccolo
-una buona idea

contano e aiutano sempre. LibreWings cresce un commit alla volta.

## Contatti
Per dubbi, idee o discussioni:
-apri un’Issue su GitHub
-usa le Discussion (se attive)
-contatta lo sviluppatore a: europaverse.studios@gmail.com

Grazie per contribuire a LibreWings!