# Prompt: Crea Pannello Visivo Camere Hotel

## OBIETTIVO
Crea un **SINGOLO FILE HTML** con un pannello di controllo camere per hotel che faccia "effetto WOW" visivamente. Il focus è l'**impatto visivo** e la **visualizzazione efficace** di molte camere simultaneamente.

## REQUISITI VISIVI CRITICI

### 1. VISUALIZZAZIONE CAMERE
- **DEVE** mostrare 50-500 camere in modo compatto ma leggibile
- Ogni camera è una **card visivamente distintiva** con:
  - Numero camera grande e leggibile
  - Stato visivo immediato (colori + icone)
  - Info ospite se occupata
  - Indicatori real-time (temperatura, allarmi)
- Layout che si adatta automaticamente allo spazio disponibile
- **Nessuno scroll** per vedere le prime 100 camere su schermo desktop

### 2. STATI CAMERE (MOLTO IMPORTANTI)
Ogni stato deve essere **immediatamente riconoscibile**:
- 🟢 **LIBERA**: Verde brillante, effetto "disponibile"
- 🔵 **OCCUPATA**: Blu professionale, mostra ospite
- 🟡 **MANUTENZIONE**: Giallo warning, icona strumenti
- 🔴 **ALLARME**: Rosso pulsante con animazione
- 🟣 **CHECK-OUT OGGI**: Viola, conto alla rovescia
- ⚫ **PULIZIA**: Grigio, progress bar

### 3. DESIGN MODERNO 2025
- **Glass morphism** o **Neumorphism** 
- **Dark theme** elegante con accenti colorati
- **Animazioni fluide** ma non eccessive
- **Micro-interazioni** al hover/click
- Font moderno e leggibile (Inter, system fonts)
- **Ombre e profondità** per gerarchia visiva

### 4. CONTENUTO CARD CAMERA
Ogni card deve mostrare (in modo compatto):
```
┌─────────────────┐
│ 204   [Suite]   │  ← Numero grande + tipo
│ ●────────────── │  ← Status bar colorata
│ 👤 Mario Rossi  │  ← Ospite (se occupata)
│ 🌡️ 22° 📅 3 notti│  ← Info rapide
│ ⚡ azioni rapide │  ← Solo su hover
└─────────────────┘
```

### 5. INTERAZIONI
- **Hover**: Card si solleva + mostra azioni rapide (luci, clima, TV)
- **Click**: Apre modal dettagliato con controlli camera
- **Filtri visuali**: Per piano, stato, ricerca ospite
- **Vista compatta/estesa**: Switch per densità informazioni

### 6. RESPONSIVE
- **Desktop**: Griglia ottimizzata per 24"+ monitor
- **Tablet**: Layout adattivo mantenendo leggibilità  
- **Mobile**: Cards verticali scrollabili

## STRUTTURA TECNICA
- **UN SOLO FILE HTML** con CSS e JS inline
- **NO framework esterni** (no React, Vue, etc.)
- **NO dipendenze CDN** (tutto autocontenuto)
- Dati simulati per 127 camere (4 piani)
- Performance fluida anche con 500+ elementi

## ESEMPI VISIVI DA EMULARE
Pensa a dashboard moderne tipo:
- Stripe Dashboard (pulizia e chiarezza)
- Linear (animazioni sottili)
- Vercel (dark theme elegante)
- Notion (organizzazione spaziale)

## OUTPUT ATTESO
Un file HTML che quando aperto mostra:
1. Dashboard immediata senza loading
2. Tutte le camere visibili in griglia intelligente
3. Effetto "wow" al primo impatto
4. Sensazione di software professionale costoso
5. Zero configurazione necessaria

## PRIORITÀ
1. **Impatto visivo** > funzionalità complete
2. **Leggibilità con molte camere** > dettagli singola camera  
3. **Performance fluida** > feature avanzate
4. **Design coerente** > personalizzazioni

**IMPORTANTE**: Il file deve stupire visivamente. Immagina di mostrarlo a un cliente hotel di lusso - deve sembrare un software da 50.000€, non un progetto amatoriale.