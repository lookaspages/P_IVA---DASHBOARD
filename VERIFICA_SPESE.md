# Prospetto spese — verifica del 23 settembre 2026

Fonte privata: `ListaMovimenti (2).pdf`, estratto del 21 settembre 2026,
52 pagine. Il documento bancario e il dettaglio dei movimenti non sono pubblicati.

- 1.187 addebiti: 48.038,56 euro, riconciliati usando importi in centesimi.
- Raggruppamento mensile e annuale per **data valuta**, non data contabile.
  Per questo i subtotali possono differire da quelli della precedente analisi.
- F24: 8 addebiti, 9.438,05 euro; inclusi 8.820,13 euro del 30 giugno 2026.
- Bollettini INPS: 12 × 64,09 = 769,08 euro; commissioni: 12 × 1,50 = 18 euro.
- Prelievi: 24 operazioni, 7.530 euro; escluse sei commissioni da 2 euro.
- Anarchia: 7.460 euro di prelievi da almeno 50 euro + 400 euro PayPal
  del 18 novembre 2025 + 90 euro Pianeta Auto + 150 euro in contanti = 8.100 euro.
  Le ultime due attribuzioni sono conferme personali nella conversazione
  «Analisi delle spese»: il rimborso di 90 euro è presunto e i 150 euro
  sono ricevuti fuori dal conto. Il totale non è una categoria bancaria
  additiva né una prova della destinazione del contante.
- Apple Store: 812 euro, valuta 10 dicembre 2025 (contabile 12 dicembre),
  e 778 euro, valuta 27 marzo 2026 (contabile 31 marzo).

Gli aggregati provvisori delle altre categorie e il residuo stimato di circa
600 euro non sono presentati come dati consolidati. Non si calcola un saldo
spendibile sottraendo questo storico dagli incassi 2026.

## Compatibilità e pubblicazione

Restano invariati la chiave locale `pivaData`, il formato degli incassi,
la sezione Fisco e l'esportazione JSON. Manifest, icona Apple e service worker
usano le icone nella radice del repository. La cache `piva-v4-spese-verificate`
sostituisce le vecchie cache dell'app; non cancella localStorage.

Verificati in Chrome con viewport da 320, 375, 390 e 768 px: navigazione,
incassi aggiunti/modificati/eliminati, conservazione dati dopo ricarica,
esportazione, sezione Fisco, installazione del service worker e uso offline.
Non è stato eseguito un test su iPhone fisico o Safari/WebKit.
