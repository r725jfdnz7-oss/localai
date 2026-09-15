# LocalAI — Supabase v1

Questa versione collega il prototipo LocalAI a Supabase.

## Cosa include
- Registrazione e login email/password
- Sessione Supabase
- Creazione/modifica dell'attività
- Clienti
- Appuntamenti
- Dashboard con conteggi
- Interfaccia AI demo pronta per il prossimo collegamento
- PWA base

## Configurazione
Apri `config.js` e inserisci:
- `SUPABASE_URL`: Project URL del progetto Supabase
- `SUPABASE_PUBLISHABLE_KEY`: Publishable key

Non inserire mai Secret Key / service_role.

## Importante
Il progetto Supabase deve avere le tabelle e le policy RLS già create. Per l'accesso degli utenti autenticati devono essere presenti i grant già configurati nel SQL Editor.

## Avvio
Per un test rapido puoi aprire `index.html` tramite un server locale/statico. Alcuni browser limitano funzioni PWA o moduli quando il file viene aperto direttamente.

Prossimo step: collegamento della Edge Function `localai-chat` con il vero motore AI.
