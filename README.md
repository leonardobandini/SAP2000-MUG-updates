# MUG — download e aggiornamenti

**[Scarica MUG 2.0.46 per Windows](https://github.com/leonardobandini/SAP2000-MUG-updates/releases/latest/download/MUG-latest.zip)** · [Release 2.0.46 e checksum](https://github.com/leonardobandini/SAP2000-MUG-updates/releases/tag/v2.0.46) · [Versione 1.0.0 e sorgenti GPL](https://github.com/leonardobandini/SAP2000-MUG-updates/releases/tag/v1.0.0)

MUG 2 combina le imperfezioni geometriche da forme di buckling e/o modali in SAP2000 27 e CSiBridge 27. Richiede Windows x64, .NET Framework 4.8 e WebView2 Evergreen. Leggi `MUG2-Guide.html` nello ZIP per le istruzioni in italiano e inglese. Prima di installare salva i modelli e chiudi SAP2000 e CSiBridge; estrai **tutto** l'archivio e avvia `MUG2Setup.exe`. La copia modificata resta aperta nell'applicazione CSI: salvala esplicitamente lì, se desideri conservarla.

**Licenza e sorgenti:** MUG 2 è freeware proprietario: lo ZIP contiene binari, asset per l'interfaccia, licenza e avvisi dei componenti terzi, ma **non** i sorgenti C# di MUG 2. Il repository di sviluppo MUG 2 è privato. I diritti GPL della precedente MUG 1 non cambiano: [la release 1.0.0](https://github.com/leonardobandini/SAP2000-MUG-updates/releases/tag/v1.0.0) conserva i suoi sorgenti, le relative licenze e i checksum.

**Aggiornamenti:** MUG 1.0.0 e MUG 2 leggono [`latest.json`](latest.json) in questo repository. La V1 scarica lo ZIP con checksum SHA-256; l'updater estrae i nuovi file e conserva un backup della precedente installazione, poi avvia il setup MUG 2 che richiede il tuo intervento. MUG 2 segnala le versioni nuove, ma download e installazione sono manuali. La V0.9.6 legge invece `https://www.leonardobandini.it/mug/latest.json`, indirizzo separato non aggiornato qui. Per installare manualmente, scarica lo ZIP sopra, estrailo e avvia `MUG2Setup.exe` dopo aver chiuso gli host CSI.

MUG 2: copyright © 2026 Leonardo Bandini, tutti i diritti riservati. MUG 1 originale: GNU GPL versione 3 soltanto.
