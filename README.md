# Wado Ichimonji — GLSL Katana for Minecraft

Questo progetto nasce con l'obiettivo di ricreare **Wado Ichimonji**, la celebre katana di *One Piece*, all'interno di **Minecraft**, utilizzando **GLSL** per ottenere una rappresentazione dettagliata e fedele direttamente tramite shader.

L'idea non è semplicemente quella di realizzare una texture ispirata alla spada, ma di sperimentare con una vera e propria **ricostruzione procedurale della katana**, sfruttando geometria, trasformazioni, materiali ed effetti calcolati direttamente lato GPU.

---

## ⚔️ Obiettivo

Il progetto mira a riprodurre l'estetica caratteristica di **Wado Ichimonji**, mantenendo riconoscibili gli elementi principali della katana:

- lama lunga e pulita;
- profilo leggermente curvo;
- finitura metallica della lama;
- **tsuba** circolare;
- impugnatura bianca;
- dettagli dorati;
- proporzioni ispirate al design originale;
- resa coerente con l'illuminazione e l'ambiente di Minecraft.

L'obiettivo finale è trovare un equilibrio tra **fedeltà al design originale**, integrazione con lo stile visivo di Minecraft e sperimentazione grafica tramite GLSL.

---

## 🧩 Implementazione

La katana viene costruita direttamente all'interno dello shader attraverso una combinazione di **primitive geometriche** e **funzioni matematiche**.

Il rendering può includere tecniche come:

- **Signed Distance Fields (SDF)**;
- primitive procedurali;
- trasformazioni di coordinate;
- rotazioni, traslazioni e scaling;
- composizione di più forme;
- calcolo delle normali;
- illuminazione personalizzata;
- materiali metallici;
- riflessi e highlight sulla lama;
- gestione procedurale dei dettagli dell'impugnatura e della guardia.

Questo approccio permette di ottenere un modello che non dipende necessariamente da una mesh tradizionale, lasciando gran parte della costruzione e del rendering direttamente alla **GPU**.

---

## 🎨 Direzione visiva

La resa grafica cerca di conservare l'identità di **Wado Ichimonji** senza farla apparire completamente estranea al mondo di Minecraft.

Particolare attenzione viene data a:

- silhouette della katana;
- leggibilità della forma anche a distanza;
- contrasto tra lama, tsuba e impugnatura;
- comportamento del metallo sotto diverse condizioni di luce;
- riflessi lungo il filo della lama;
- dettagli capaci di rendere immediatamente riconoscibile la spada.

L'obiettivo non è necessariamente ottenere un risultato fotorealistico, ma una versione **stilizzata, pulita e tecnicamente interessante** della katana.

---

## 🛠️ Tecnologie

- **Minecraft**
- **GLSL**
- Shader Pack / Rendering Pipeline compatibile
- Rendering procedurale
- **Signed Distance Fields**
- **Raymarching**, dove applicabile

---

## 🚧 Stato del progetto

Il progetto è attualmente **in sviluppo**.

Le varie parti della katana vengono progressivamente costruite e rifinite separatamente, per poi essere integrate nel modello finale.

### Roadmap

- [ ] Forma definitiva della lama
- [ ] Curvatura e profilo del filo
- [ ] Punta della katana
- [ ] Tsuba
- [ ] Habaki e dettagli metallici
- [ ] Impugnatura
- [ ] Pattern dell'avvolgimento
- [ ] Pomolo
- [ ] Materiali
- [ ] Illuminazione
- [ ] Riflessi metallici
- [ ] Ottimizzazione GLSL
- [ ] Integrazione definitiva in Minecraft

---

## 🧪 Scopo del progetto

Oltre alla realizzazione di **Wado Ichimonji**, questo progetto rappresenta anche un esercizio di sperimentazione con il **rendering procedurale in GLSL**.

La katana viene utilizzata come soggetto per approfondire:

- modellazione tramite matematica;
- costruzione di geometrie attraverso SDF;
- gestione degli spazi di coordinate;
- shading;
- illuminazione;
- materiali;
- ottimizzazione delle operazioni eseguite per pixel;
- integrazione di elementi complessi nella pipeline grafica di Minecraft.

L'obiettivo del progetto è quindi sia **artistico** sia **tecnico**.

---

## 📌 Disclaimer

Questo è un progetto **fan-made e non commerciale**, realizzato a scopo di studio, sperimentazione e divertimento.

**Wado Ichimonji**, *One Piece* e i relativi personaggi e design appartengono ai rispettivi detentori dei diritti.

Il progetto non è affiliato, sponsorizzato o approvato ufficialmente dai proprietari dell'opera originale.
