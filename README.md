# Void SMS Bot

> Servizio di numeri temporanei italiani per la verifica SMS via Telegram

![Void SMS](https://img.shields.io/badge/Telegram-Bot-blue?style=flat-square&logo=telegram)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![Security](https://img.shields.io/badge/Security-AES--256--GCM-orange?style=flat-square)

---

## Cos'è Void SMS?

Void SMS è un servizio che ti permette di ricevere codici di verifica SMS senza usare il tuo numero di telefono personale. Ideale per:

- 🔒 **Proteggere la tua privacy** - Nessuna associazione tra il tuo numero e i tuoi account
- 📱 **Verifiche multiple** - Un numero usa e getta per ogni servizio
- ⚡ **Velocità** - Ricevi il codice in pochi secondi
- 🇮🇹 **Numeri italiani** - Servizi che richiedono numeri italiani

---

## Come Funziona

### 1. Acquista Crediti

Scegli un pacchetto di crediti tramite il menu del bot. I crediti non hanno scadenza e vengono scalati solo quando ricevi effettivamente un SMS.

### 2. Seleziona il Servizio

Scegli il servizio per cui ti serve la verifica (Instagram, Telegram, Netflix, ecc.) e la categoria del numero.

### 3. Ricevi il Numero

Il bot ti fornirà un numero italiano temporaneo. Inseriscilo nel servizio che stai verificando.

### 4. Ricevi il Codice

Il codice SMS arriverà automaticamente nel bot entro pochi minuti.

---

## Servizi Supportati

| 💬 Messaggistica | 📸 Social | 🛒 Shopping |  🎬 Intrattenimento | 📧 Mail & Altro |
|----------|----------|----------|----------|----------|
| Telegram ✈️ | Instagram 📸 | Amazon 🛒 | Spotify 🎵 | Google/Gmail 📩 |
| WhatsApp ✅ | Discord 🎮 | Vinted 👕 | Netflix 📺 | ProtonMail 📧 |
| Signal 🔵 | TikTok 🎵 | Deliveroo 🍕 | Steam 🎮 | Apple 🍎 |
| Viber 📱 | Facebook 👍 | Uber 🚗 | | PayPal 🅿️ |
| | Twitter (X) 🐦 | | | ChatGPT 🤖 |
| | Snapchat 👻 | | |
| | Tinder 💘 | | |

---

## Sicurezza & Crittografia

### 🛡️ Protezione dei Dati

Tutti i dati sensibili sono protetti con **crittografia AES-256-GCM**, uno standard militare utilizzato anche da banche e governi.

```
Algoritmo: AES-256-GCM
Derivazione chiave: PBKDF2 con 100.000 iterazioni
Protezione IV: Random a 96 bit per ogni operazione
```

### 🔑 Gestione delle Chiavi

- Le chiavi di crittografia sono archiviate in modo sicuro e **mai accessibili** al personale
- Ogni dato è isolato con un vettore di inizializzazione unico (IV)
- Sistema di versionamento per futura rotazione delle chiavi

### 🚫 Cosa NON Archiviaamo

- ❌ Numeri telefonici acquistati
- ❌ Contenuto degli SMS ricevuti
- ❌ Dati personali
- ❌ Indirizzi IP
- ❌ Log di navigazione
- ❌ Cronologia delle verifiche

### ⚠️Nota Importante sulla Blockchain

Le transazioni Bitcoin sono pubbliche e permanenti sulla blockchain. Se usi BTC, chiunque può vedere il tuo indirizzo sulla blockchain.

---

## Privacy

### 🥷 La Tua Anonimità

| Aspetto | Protezione |
|---------|------------|
| Identità | Zero dati personali richiesti |
| Numeri | Temporanei, mai associati a te |
| SMS | Non salvati dopo la consegna |
| Pagamenti | Dati carta gestiti da terzi |

### 📋 Dati che Raccogliamo

Per offrirti il servizio, archiviamo solo:

1. **Chat ID Telegram** - Per inviarti i codici
2. **Crediti** - Il tuo saldo di crediti
3. **Metodo di pagamento** - Solo per elaborare il pagamento (tramite provider esterni)

### 🏦 Dati di Pagamento

| Metodo | Gestione |
|--------|----------|
| 💳 Carta/Stripe | Elaborati direttamente da Stripe, noi non vediamo mai i dati della carta |
| ⭐ Stelle Telegram | Elaborate da Telegram, conformi alle loro policy |
| ₿ Bitcoin | Nessun dato personale necessario |

---

## Metodi di Pagamento

### 💳 Carta di Credito/Debito
- Visa, Mastercard, American Express
- Apple Pay, Google Pay supportati
- Elaborazione tramite **Stripe** (certificazione PCI-DSS)

### ⭐ Stelle Telegram
- Pagamento istantaneo
- Conversioni preferenziali
- Nessun dato personale

### ₿ Bitcoin
- Pagamento on-chain
- Conferma in ~10-30 minuti
- Zero dati personali richiesti
- L'indirizzo viene eliminato automaticamente dopo 24 ore se non utilizzato

---

## Sistema di Crediti

### 💰 Come Funziona

1. I crediti **non scadono mai**
2. Vengono **scalati solo** quando ricevi un SMS
3. Se annulli un ordine o scade, **nessun credito viene detratto**

### 📊 Costo per Servizio

Il costo in crediti varia in base al prezzo che i nostri provider applicano per quel servizio. I prezzi sono calcolati automaticamente in modo trasparente.

---

## Termini di Servizio

### 1. Oggetto del Servizio
Void SMS fornisce numeri telefonici temporanei italiani per la ricezione di codici di verifica SMS.

### 2. Utilizzo
- Il servizio deve essere usato per **scopi legittimi**
- È vietato l'uso per attività illegali o fraudolente
- L'utente è responsabile dell'uso che fa del servizio

### 3. Pagamenti
- I pagamenti sono **definitivi e non rimborsabili**
- I crediti non hanno scadenza
- Metodi accettati: carta, Stelle Telegram, Bitcoin

### 4. Limitazione di Responsabilità
- **Non garantiamo** la disponibilità dei numeri
- **Non siamo responsabili** per mancata ricezione SMS
- **Non siamo responsabili** per problemi tecnici dei provider esterni
- **Non siamo responsabili** per danni diretti o indiretti

### 5. Disposizioni Generali
- Ci riserviamo il diritto di modificare i termini in qualsiasi momento
- L'uso continuato del servizio implica l'accettazione dei termini

---

## FAQ

### Quanto tempo ho per ricevere l'SMS?
Hai **10 minuti** di tempo una volta ottenuto il numero. Se non arriva nessun SMS, il numero viene rilasciato automaticamente e non viene addebitato nulla.

### Cosa succede se il numero non funziona?
Puoi annullare l'ordine e richiedere un nuovo numero. Nessun credito verrà scalato.

### Posso usare lo stesso numero per più servizi?
Ogni numero è per un singolo servizio. Per verifiche multiple, dovrai richiedere numeri separati.

### I numeri sono italiani?
Sì, forniamo esclusivamente numeri italiani.

### Posso avere un rimborso?
I crediti acquistati non sono rimborsabili. Assicurati di acquistare la quantità adeguata alle tue esigenze.

---

## Contatti

- 💬 **Supporto**: @mnnotclr [telegram]

---

## Ultimo Aggiornamento

**28/03/2026** - Versione corrente dei termini e della privacy policy
