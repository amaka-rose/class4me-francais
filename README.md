# Class 4 Me Français

App per il telefono per arrivare alla certificazione **B2 di francese** (DELF B2 oppure TCF/TEF Canada), partendo da basi scolastiche.

È una web app installabile (PWA): si apre dal browser e si aggiunge alla schermata Home, su iPhone e su Android. Non serve uno store.

## Cosa fa

- **Percorso**: 27 unità in 5 fasi (riattivazione, A2, B1, B2, preparazione all'esame DELF B2 o TCF Canada), ognuna con obiettivo, grammatica, esempi, attività e verifica; calendario aggiornato sul ritmo reale e sulla data dell'esame.
- **Oggi**: la sessione del giorno (parole, ascolto, pronuncia, verbi, missione parlata o scritta, compito d'esame).
- **Ascolta**: dialoghi in 5 passi (ascolto, domande, riascolto lento con testo, dettato, velocità piena), voce francese di Francia o del Québec.
- **Pronuncia**: suoni nasali, u/ou, e muta, r, liaison, é/è; verifica con la dettatura.
- **Verbi**: présent, passé composé, imparfait, futur.
- **Parole**: ripasso spaziato, genere a colori, parole personali.
- **Esame**: formato DELF B2 o TCF Canada, letture, scrittura con voto su 25, prova orale.
- **Progressi**: ore fatte rispetto alle ore stimate, livello per abilità, copia di sicurezza.

## Intelligenza artificiale

Conversazioni, correzioni e dialoghi nuovi usano:
- **Claude**, quando l'app è aperta come artefatto dentro claude.ai;
- **Groq** (modelli open source, piano gratuito con limiti) quando l'app gira da sola: la chiave si inserisce in *Progressi › Impostazioni* e resta solo sul dispositivo.

Senza chiave l'app funziona comunque: le attività con l'AI offrono un pulsante «Copia per Claude».

## Installare sul telefono

1. Apri l'indirizzo GitHub Pages del repository.
2. iPhone: Safari › Condividi › *Aggiungi alla schermata Home*. Android: Chrome › menu › *Installa app*.
3. Per la voce: installa una voce francese nelle impostazioni del telefono (Accessibilità › Contenuto letto ad alta voce › Voci).

## Pubblicare con GitHub Pages

Settings › Pages › *Deploy from a branch* › `main` / `root`.

## Dati e privacy

I progressi restano nel browser del dispositivo (localStorage). All'esterno escono solo i testi inviati al servizio AI scelto. Nessun account, nessun tracciamento.

## Licenza

MIT.
