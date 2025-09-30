
# Wedding Site (GitHub Pages) — Istruzioni rapide

Questa cartella contiene un sito **one-page** gratuito, pronto per GitHub Pages.

## 1) Crea il repository
1. Su GitHub, crea un repo pubblico chiamato, ad esempio, `wedding-site`.
2. Carica `index.html` in root (trascina e rilascia su GitHub).

## 2) Attiva GitHub Pages
1. Vai su **Settings → Pages**.
2. In **Build and deployment**, scegli **Source: Deploy from a branch**.
3. `Branch: main` e `Folder: /root` → **Save**.
4. Il sito sarà disponibile su: `https://<tuo-utente>.github.io/wedding-site/`.

## 3) Personalizza i contenuti
- Apri `index.html` e cerca il blocco `// === CONFIGURA QUI I TUOI DATI ===`.
- Modifica nomi, data, luoghi, IBAN, email, link lista nozze, hotel.
- Sostituisci l'immagine di copertina con una vostra foto: carica la foto nel repo e aggiorna il campo `src` del tag `<img>`.

## 4) Inserisci l'RSVP (Google Forms)
1. Crea un Google Form con: nome, email, partecipo sì/no, accompagnatori, bambini, allergie, navetta, consenso privacy.
2. In **Invia → <> Incorpora**, copia l'URL di embed.
3. Incolla quell'URL nella variabile `config.rsvpFormUrl` (in `index.html`).

## 5) Aggiungi le mappe
- Apri Google Maps, cerca la chiesa/venue → **Condividi → Incorpora una mappa** → copia l'URL `<iframe>`.
- Incolla solo la parte `src` nelle variabili `config.ceremony.mapsEmbed` e `config.reception.mapsEmbed`.

## 6) Dominio personalizzato (opzionale)
- Puoi usare un dominio tipo `mario-giulia-2026.it` creando un record `CNAME` verso `username.github.io` e aggiungendo un file `CNAME` nel repo con il dominio dentro.

## 7) Privacy
- C'è una sezione Privacy minimale. Se serve, personalizzala con vostre note/contatti.

Buona festa! 💍
