# DiToM Screening Analys

🎯 **Professionell analysverktyg för DiToM 2+ och DiToM 4+ screeningresultat**

En webbaserad lösning för lärare som vill analysera elevernas matematiska nivå, få personliga rapporter och klassöversikter.

## ✨ Funktioner

- ✅ **Två DiToM-versioner**: Stöd för både DiToM 2+ (År 2-3) och DiToM 4+ (År 4-6+)
- ✅ **Anpassningsbara gränsvärden**: Justera Grupp A/B/C-klassificering efter dina behov
- ✅ **Copy-paste import**: Enkelt att importera data direkt från Excel
- ✅ **Personliga elevrapporter**: Detaljerade analyser per elev
- ✅ **Klassöversikt**: Se klassens styrkor och utmaningar
- ✅ **Jämförelser**: Identifiera elever med högsta behov av stöd i varje område
- ✅ **PDF-export**: Ladda ner personliga rapporter
- ✅ **Sessionssparing**: Dina data sparas lokalt i webbläsaren
- ✅ **Offline-funktion**: Fungerar helt utan internetanslutning

## 🚀 Snabbstart

### Metod 1: Använd HTML-filen direkt
1. Ladda ner `index.html`
2. Öppna filen i webbläsaren (dubbelklick)
3. Börja analysera dina elevresultat!

### Metod 2: 
1. Besök: `https://speciallararemaria.github.io/math-screening-tool/`

## 📝 Så använder du verktyget

### Steg 1: Välj DiToM-version
- Gå till fliken **"Inställningar"**
- Välj **DiToM 2+** eller **DiToM 4+**

### Steg 2: Justera gränsvärden (valfritt)
- Standardgränsvärden är inställda enligt DiToM-riktlinjer
- Du kan justera gränsvärden för Grupp A, B och C
- Klicka **"Spara gränsvärden"**

### Steg 3: Importera elevdata
- Gå till fliken **"Importera data"**
- Öppna din Excel-fil med elevresultaten
- **Kopiera** alla rader (Namn | År | Uppgifter | Total poäng)
- **Klistra in** i textrutan
- Klicka **"Importera"**

### Steg 4: Analysera resultaten

**Individuella rapporter** (fliken "Individuella rapporter"):
- Välj elev från dropdown-listan
- Se detaljerad rapport med styrkor och utvecklingsområden
- Ladda ner som PDF

**Klassöversikt** (fliken "Klassöversikt"):
- Se hur många elever i Grupp A/B/C
- Se klassens övergripande styrkor och utmaningar
- Tabell över alla elever

**Jämförelser** (fliken "Jämförelse"):
- Identifiera vilka elever som behöver mest stöd per uppgift
- Se vilka områden som behöver fokus för varje elev

## 📊 Datformat

### För DiToM 2+ (15 uppgifter):
```
Namn	År	Uppg1	Uppg2a	Uppg2b	Uppg2c	...	Uppg15	Total
Filip	2	1	0.5	1	0	...	0	12
Sara	3	1	1	1	1	...	1	14
```

### För DiToM 4+ (16 uppgifter):
```
Namn	År	Uppg1	Uppg2a	Uppg2b	Uppg2c	...	Uppg13c	Total
Erik	4	1	1	0.5	0	...	1	13
Maria	5	0.5	1	1	1	...	0.5	11
```

**Tips:**
- Använd **Tab-tecken** för att separera kolumner (auto när du kopierar från Excel)
- **Total poäng** räknas automatiskt
- Använd **0**, **0.5** eller **1** för poäng

## 🎯 Grupp A/B/C Klassificering

**Standard DiToM-klassificering (kan justeras):**

- **Grupp A** (Omfattande svårigheter): ≤5 poäng (DiToM 2+) / ≤5 poäng (DiToM 4+)
  - Elever som kan behöva omfattande stöd
  - Följ upp med individuell bedömning

- **Grupp B** (Specifika områden): 6-10 poäng (DiToM 2+) / 6-11 poäng (DiToM 4+)
  - Elever med utmaningar i vissa områden
  - Riktat stöd rekommenderas

- **Grupp C** (Inga direkta tecken): 11-15 poäng (DiToM 2+) / 12-16 poäng (DiToM 4+)
  - Elever utan direkta tecken på svårigheter
  - Regelbunden klassundervisning

## 💾 Dataskydd

- ✅ **All data sparas LOKALT** i din webbläsare
- ✅ **Inget skickas till någon server**
- ✅ **Ingen data lagras online**
- ✅ **Du har full kontroll** över dina elevdata
- ✅ **GDPR-kompatibel** (data lämnar aldrig din maskin)

## 🔄 Sessionssparing

- Dina inställningar och elevdata sparas automatiskt
- Nästa gång du öppnar verktyget är allt kvar
- Du kan rensa data manuellt när du vill

## 📥 Export

- **PDF**: Ladda ner personliga elevrapporter
- **Klassöversikt**: Visa all klassdata i tabellformat
- **Jämförelser**: Se övergripande mönster

## 🛠️ Teknik

- **HTML5** + **CSS3** (Tailwind)
- **JavaScript** (vanilla, ingen dependencies)
- **LocalStorage** (datasparing)
- **html2pdf** (PDF-export)
- **Responsive design** (fungerar på desktop, tablet, mobil)

## 📚 Bakgrund - DiToM

**DiToM** är en vetenskapligt utvecklad screeningmetod för att identifiera elever som kan behöva extra stöd i matematik.

- **Fokus på "key skills"** - grundläggande matematiska färdigheter
- **Hierarkisk struktur** - förebygger senare svårigheter
- **Inte en diagnos** - en screening som utgångspunkt för vidare observation
- **Utvecklat i 7 länder** - testat på 8820+ elever

### DiToM 2+
- **Årskurser**: 2-3
- **Fokusområden**: Positionssystem, tal, addition, subtraktion, huvudräkning
- **Totalt poäng**: 15

### DiToM 4+
- **Årskurser**: 4-6+
- **Fokusområden**: Större tal, multiplikation, division, platsvärde
- **Totalt poäng**: 16

## 👥 Stöd & Samarbete

Denna tool är utvecklad för svenska lärare som använder DiToM-screeningen.

**Frågor eller förslag?** Öppna en issue på GitHub.

## 📄 Licens

Denna tool är öppen för alla lärare att använda, modifiera och dela.

---

**Lycka till med dina analyser!** 🎓
