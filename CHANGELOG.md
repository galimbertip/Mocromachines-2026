# Changelog — Micro Rush

Schema `V.major.minor.patch`.

## v1.7.0 — 19 novembre 2026 (motore 3D e visuali)

- Nuovo motore 3D in WebGL2 scritto a mano, senza librerie esterne: la fisica resta identica, cambia solo la grafica.
- Tre visuali: dall'alto (la classica, unica in Eliminazione), 3/4 inclinata alla World Rally, da dietro alla Out Run. Si sceglie nel menu o in gara con il tasto V o il pulsante in alto.
- Auto, motoscafi e Big Foot low-poly con ruote che sterzano e luci dei freni; oggetti di casa in rilievo, sponde, tunnel e giro della morte in 3D; il tavolo è sollevato dal pavimento e la caduta si vede.
- Senso di velocità nella visuale da dietro: il campo visivo si allarga con la velocità e con il nitro.
- Qualità automatica: sui telefoni lenti la risoluzione 3D scende da sola.
- Se il dispositivo non supporta WebGL2 il gioco resta nella visuale dall'alto.
- Tempo di riferimento della Vasca da bagno ricalibrato sul tracciato definitivo.

## v1.6.0 — 19 novembre 2026 (scorciatoie e cabinati anni 80/90)

- Scorciatoie alla World Rally su Colazione, Scrivania, Giardino e Pista arancione: passaggi stretti segnati da paletti gialli che tagliano un pezzo di pista. Anche gli avversari a volte le prendono, più spesso in Difficile.
- Nitro alla Super Off Road: 2 cariche a gara (massimo 3) e bombole N2O da raccogliere in pista. Spazio per P1, Q per P2, Y/RB sul gamepad, pulsante N2O sul touch.
- Campionato alla Super Sprint: una chiave inglese nascosta in ogni gara più una per ogni vittoria; tra una gara e l'altra l'officina migliora aderenza, accelerazione e velocità (3 livelli ciascuna). Un rivale campione (★) diventa più forte ogni volta che vinci. Con migliorie attive i record non vengono salvati.
- Pericoli: sulla Scrivania un phon che soffia di traverso a intermittenza e un cassetto che si apre e chiude bloccando la scorciatoia.
- Nuova pista Vasca da bagno (anche nella Coppa Casa, che diventa di 4 gare): si corre tutti in motoscafo, tra paperelle che galleggiano e il gorgo dello scarico che risucchia e fa girare.
- Regola extra Armi giocattolo (facoltativa, alla Badlands): 3 elastici a gara che fanno girare chi colpisci. F per P1, E per P2, LB sul gamepad, pulsante 🎯 sul touch.

## v1.5.0 — 19 novembre 2026 (campionato, pista del giorno, Big Foot)

- Nuovo mezzo Big Foot: pick-up con ruote enormi, pesante, non teme l'erba e passa sopra gli oggetti piccoli (zollette, funghi, gessi).
- Campionato: Coppa Casa (Colazione, Scrivania, Biliardo) e Coppa Giochi (Giardino, Spiaggia, Pista arancione), punti 10-6-3-1, classifica dopo ogni gara e premiazione finale.
- Pista del giorno: ogni giorno una pista nuova generata dalla data, con ambiente a sorpresa; record e medaglie valgono solo per quel giorno.
- Luci classiche: in Eliminazione a due giocatori, 4 luci a testa, chi vince il round ne ruba una, vince chi le prende tutte e 8.

## v1.4.0 — 19 novembre 2026 (pista arancione, regole extra, livree)

- Avviso di curva alla World Rally: al posto della scritta, una freccia piegata quanto la curva in arrivo, colorata in base alla difficoltà.
- Nuova pista "Pista arancione", ispirata alle piste giocattolo Hot Wheels: plastica arancione con sponde e raccordi blu, booster con le ruote che spingono, giro della morte (serve velocità, altrimenti si torna indietro) e salto nel vuoto sopra un pezzo di pista mancante.
- Regole extra attivabili: pista ghiacciata, auto giganti, gravità lunare. Con le regole attive record e fantasmi non vengono salvati.
- Livrea: colore e numero della tua auto; numeri anche sugli avversari.

## v1.3.0 — 19 novembre 2026 (mezzi e piste)

- Quattro mezzi con guida diversa: Sportiva; Fuoristrada (non rallenta fuori pista e pesa di più negli urti); Formula 1 (velocissima e incollata alla pista, ma soffre l'erba e gli urti); A carica (scatto forte ma la molla si scarica: fermati e tieni FRENO per ricaricarla).
- Due piste nuove: Biliardo (sponde che respingono, sei buche in cui cadere, palle da spingere) e Biglie in spiaggia (pista nella sabbia con sponde, gallerie e biglie giganti che rotolano lungo il percorso).
- Pericoli che si muovono: arancia che rotola sulla Colazione, pallina di carta sulla Scrivania, robot tosaerba che attraversa il Giardino.
- Rampe: libri e assi di legno fanno saltare le auto; in volo si passa sopra ostacoli e buche.
- Record, fantasma e medaglie separati per mezzo, con tempi obiettivo adattati.

## v1.2.0 — 8 novembre 2026 (guida e sfida)

- Si cade dal tavolo: Colazione e Scrivania hanno i bordi del mobile e sotto c'è il pavimento. In Gara e Prova a tempo rientri in pista, in Eliminazione sei fuori dal round.
- Scia: stando dietro a un'auto veloce guadagni velocità.
- Turbo da derapata: una derapata lunga (scintille blu, poi arancioni) ricarica un turbo quando la chiudi.
- Spintone: se butti giù dal tavolo o fuori dallo schermo un rivale appena urtato, rallentatore, bonus turbo e scritta SPINTONE!
- Nuova modalità Prova a tempo: 5 giri da solo, auto fantasma del giro migliore, medaglie Bronzo / Argento / Oro / Autore per pista.
- Le medaglie conquistate compaiono sulle schede delle piste.

## v1.1.1 — 8 novembre 2026

- Corretto: si passava attraverso matite, cucchiai, gomme, piatti, zollette di zucchero e funghi. Ora sono ostacoli solidi con la loro forma reale (le matite sono lunghe e sottili). Restano calpestabili solo gli oggetti piatti: post-it, graffette, foglie e fiori.

## v1.1.0 — 8 novembre 2026 (leggibilità e accessibilità)

- Telecamera che guarda avanti nella direzione di marcia e si allarga un poco ad alta velocità.
- Cartelli a chevron sul bordo esterno delle curve strette e avviso "copilota" in alto (‹‹ SINISTRA / DESTRA ››), con più frecce se la curva è più stretta.
- Tre livelli di difficoltà: Facile, Normale, Difficile.
- Aiuto alla guida opzionale: più aderenza e frenata automatica se arrivi troppo forte in curva (attivo in automatico con Facile).
- Sterzo touch analogico: tieni premuto e trascina il pollice; i tasti ◀ ▶ restano come alternativa.
- Tasti touch più grandi e opzione per mancini.
- Rientro automatico in pista dopo 3 secondi fuori pista o bloccati.
- Riavvio istantaneo: tasto R o pulsante ↻.
- Mini tutorial alla prima partita.

## v1.0.0 — 7 novembre 2026

- Prima versione: corse in miniatura viste dall'alto.
- Modalità Gara (4 giri contro 3 avversari IA) ed Eliminazione (chi esce dallo schermo è fuori, vince chi arriva a 5 round; se il round dura troppo lo schermo si stringe).
- Tre piste: Colazione, Scrivania, Giardino; le pozze riducono l'aderenza.
- Fisica arcade con derapata, segni di frenata permanenti, polvere e scintille.
- Effetto miniatura (tilt-shift) disattivabile.
- Controlli: tastiera (P1 frecce, P2 WASD), gamepad, touch con gas automatico.
- Audio sintetizzato, record del giro salvati nel browser.
