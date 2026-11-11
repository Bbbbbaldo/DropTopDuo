# Scrivania a muro con ribalta e sollevamento elettrico (fai da te)

Una postazione di lavoro che vive appesa al muro: un mobile poco profondo con due monitor da 27", chiuso da un piano a ribalta che diventa la scrivania. Il tutto sale e scende elettricamente, da seduti a in piedi, su due gambe motorizzate fissate alla parete e non al pavimento.

> ⚠️ **Progetto personale, non verificato da un ingegnere.** Leggi la sezione [Sicurezza e responsabilità](#sicurezza-e-responsabilità) prima di costruire qualsiasi cosa.

---

## Indice

- [Come funziona](#come-funziona)
- [Misure principali](#misure-principali)
- [Il percorso del carico](#il-percorso-del-carico)
- [Componenti](#componenti)
  - [Sollevamento](#1-sollevamento)
  - [Struttura di ferro](#2-struttura-di-ferro)
  - [Legno](#3-legno)
  - [Piano a ribalta](#4-piano-a-ribalta)
  - [Monitor ed elettrico](#5-monitor-ed-elettrico)
- [Distinta di taglio del legno](#distinta-di-taglio-del-legno)
- [Ordine di montaggio](#ordine-di-montaggio)
- [Note sulla FlexiSpot](#note-sulla-flexispot)
- [Punti ancora aperti](#punti-ancora-aperti)
- [Sicurezza e responsabilità](#sicurezza-e-responsabilità)
- [Ispirazione](#ispirazione)
- [Licenza](#licenza)

---

## Come funziona

- **Chiuso** è un pannello a muro di 135 × 80 cm, profondo circa 35 cm dal muro, con un quadro sul davanti e una serratura a chiave.
- **Aperto**, il pannello frontale ruota di 90° su una cerniera a pianoforte e diventa il piano di lavoro. Lo reggono due cavi d'acciaio; due pistoni a gas servono solo a frenare la discesa.
- **Altezza**: due gambe elettriche FlexiSpot, montate in verticale sul muro, sollevano tutto il mobile. A riposo il piano è a 73 cm (seduti); in piedi sale a circa 110 cm. La corsa massima è 49 cm.

Le gambe fanno sia da motore sia da guida: niente rotaie lineari. Funziona perché le gambe sono bloccate al muro in due punti ciascuna, sono parallele e a piombo, e una struttura rigida le collega in cima.

---

## Misure principali

| Cosa | Misura |
|---|---|
| Mobile (L × A × P) | 135 × 80 × 22 cm |
| Piano a ribalta | 131 × 78 cm |
| Monitor | 2 × 27" (62 × 37 cm ciascuno) |
| Interasse gambe | 110 cm |
| Piano da seduti | 73 cm da terra |
| Piano in piedi | ~110 cm (max 122) |
| Cima del mobile | da 153 a ~190 cm |
| Peso stimato del mobile completo | ~60–65 kg |
| Portata delle gambe (dichiarata) | 100 kg |

---

## Il percorso del carico

Sezione di lato, al centro di una gamba (dal muro verso la stanza):

```
 muro │ listone │ listello │  gamba (tubo 43×75)  │ omega │   │ lastra │ schiena │ ── mobile ──▶
      │  28 mm  │  12 mm   │                      │ 4 mm  │   │  2 mm  │  18 mm  │
                            ▲ spinta della gamba
                            │ sullo stesso asse della piega della lastra
```

1. Il mobile è avvitato alla **lastra a L** (parte verticale alta 45 cm).
2. La **piega** in cima alla lastra poggia sulla testa delle due gambe, centrata sul loro asse.
3. Le **gambe** spingono verso il basso sulla **staffa a mensola**, che porta il peso al muro.
4. Quando ci si appoggia al piano aperto, il mobile tende a ruotare in avanti: questa leva la reggono le gambe, tenute contro il muro da due **morsetti a omega** ciascuna.

---

## Componenti

### 1. Sollevamento

| Pezzo | Note |
|---|---|
| FlexiSpot E1W Pro (E1W-PRO-EUV5), doppio motore | Si usano solo le 2 gambe, la centralina e la pulsantiera. Piedi lunghi, traversa e piano originali non servono. |

Misure reali delle gambe:

- tubo grosso **43 × 75 mm**, con il lato da 75 verso la stanza (più rigido contro la leva in avanti);
- altezza da **66 a 115 cm** (corsa 49 cm);
- in basso c'è la **scatola del motore**, **19 × 10 × 5,5 cm**, con il tubo a un'estremità. Va montata con il lato da 19 lungo il muro, rivolta verso il centro. **Non forarla.**

### 2. Struttura di ferro

| Pezzo | Q.tà | Cosa chiedere al fabbro / ferramenta |
|---|---|---|
| Lastra a L | 1 | Lamiera 2 mm, nera (DC01) da verniciare dopo, larga 1200 mm. Piega in alto 102 mm con 4 fori per gamba (come la testa della gamba). Parte verticale 450 mm con 12 fori Ø 7 per la schiena e 4 per il supporto monitor. |
| Rinforzo della piega | 1 + 4 + 2 | Tubo 40 × 40 × 2 mm lungo 1000 mm saldato nell'angolo della piega (cordoni di ~3 cm ogni 15 cm). 4 fazzoletti triangolari 120 × 80 × 4 mm, uno per lato di ogni gamba. 2 piastre 120 × 100 × 6 mm sopra la piega, una per testa di gamba, con gli stessi 4 fori. |
| Morsetti a omega | 4 | Lamiera 4 mm piegata, alta 100 mm. Interno 47 × 90 mm (tubo + listello 12 mm + gomma 2 mm). Ali da 40 mm con 2 fori Ø 9 ciascuna. Due per gamba, **solo sul tubo grosso**. |
| Staffe a mensola | 2 | Ala 260 × 200 × 6 mm con 4 fori Ø 11. Braccio a vaschetta: fondo 200 × 104 × 8 mm, bordo da 30 mm davanti e ai lati, forato in corrispondenza dei fori che la scatola del motore ha sui fianchi. Fazzoletto da 6 mm saldato sotto. |
| Squadrette interne | 4 | Angolari 40 × 40 mm tra schiena e fianchi del mobile. |
| Tasselli chimici M10 | 20 | Barre M10 da 15 cm, dado, rondella, resina (1 cartuccia da 300 ml). |
| Barre M8 per gli omega | 16 | Barre M8 da 18 cm incollate nel muro con la stessa resina; dadi autobloccanti. |
| Bulloneria | 16 | 12 × M6 × 40 (lastra–schiena), 4 × M6 × 50 (supporto monitor), rondelle larghe Ø 25. |

Costo stimato del ferro: **~180–290 €** (prezzi indicativi, autunno 2026).

> Perché la lamiera da 2 mm va bene **solo con i rinforzi**: il tubo nell'angolo regge la torsione tra le gambe; senza le piastre da 6 mm sopra le teste delle gambe, la lamiera sottile si deformerebbe intorno alle viti.

### 3. Legno

| Pezzo | Materiale |
|---|---|
| Mobile (schiena, fianchi, cielo, fondo) e piano a ribalta | Abete lamellare 18 mm |
| Listoni a muro (2 × 29 × 90 cm) | Abete lamellare 28 mm |
| Listelli dietro le gambe (2 × 43 × 445 mm) | Multistrato 12 mm |

Consigli:

- lascia acclimatare i pannelli in casa 3–4 giorni prima di tagliarli;
- tratta **entrambe le facce** del piano a ribalta allo stesso modo, o si imbarca;
- unisci il mobile con spinotti e colla o con viti confirmat, non con viti nella testa del legno.

### 4. Piano a ribalta

| Pezzo | Q.tà | Note |
|---|---|---|
| Cerniera a pianoforte | 1–2 | Apertura 180°, lungo tutto il bordo inferiore. |
| Pistoni a gas per ribalta (es. Livenza Compact) | 2 | Solo freno della discesa, non reggono il carico. |
| Cavo d'acciaio Ø 4 mm + tenditori | 2 | Reggono il piano aperto. |
| Serratura a chiave (es. Meroni 2772) | 1 | |
| Calamite | 2 | Tengono chiuso il piano senza chiave. |

### 5. Monitor ed elettrico

- **Supporto monitor**: barra doppia VESA 100 × 100 **fissa** (profonda ~3 cm), avvitata con 4 bulloni M6 passanti nella schiena e nella lastra, che fa da contropiastra.
- **Prese**: multipresa da incasso nel fianco destro (Schuko + USB-A + USB-C) e una ciabatta interna per monitor e centralina, con un solo cavo che scende al muro in una guaina.
- La **centralina FlexiSpot** va avvitata ferma e in piano sopra il cielo del mobile (vedi sotto).

---

## Distinta di taglio del legno

Da 2 tavole di abete lamellare 120 × 250 cm, sp. 18 mm:

| Tavola | Pezzi |
|---|---|
| 1 | Schienale 135 × 80 · cielo 131 × 22 · 2 fianchi 80 × 22 |
| 2 | Piano a ribalta 131 × 78 · fondo 131 × 22 |

Da 1 tavola di abete lamellare 100 × 60 cm, sp. 28 mm: 2 listoni 29 × 90 cm.

---

## Ordine di montaggio

1. **Traccia sul muro** l'asse delle due gambe (interasse 110 cm), a piombo. Verifica il tipo di muro: i tasselli chimici vanno bene su pieno e semipieno; su cartongesso questo progetto **non** va bene.
2. **Listoni e staffe**: fissa i listoni con i tasselli chimici M10, poi le staffe a mensola. Controlla che i bracci delle staffe siano alla stessa quota e in bolla.
3. **Gambe**: appoggia la scatola del motore nella vaschetta e avvitala nei suoi fori laterali. Metti il listello da 12 mm e la gomma, poi i due omega. Stringi senza esagerare: se il tubo si stringe troppo scatta l'anticollisione.
4. **Prova a vuoto** le gambe con la centralina, prima di caricarle.
5. **Lastra a L**: avvitala sulle teste delle gambe con le piastre da 6 mm sopra.
6. **Mobile**: montalo a terra, poi avvitalo alla lastra con i bulloni M6 passanti.
7. **Centralina**, prese, monitor, cablaggio.
8. **Piano a ribalta**: cerniera, cavi, pistoni, serratura. Regola i tenditori con il piano in bolla.
9. **Collaudo**: salita e discesa a vuoto, poi con carico crescente; controlla gioco e serraggi dopo una settimana.

---

## Note sulla FlexiSpot

- L'**anticollisione** usa un sensore di movimento dentro la centralina: deve stare **ferma e orizzontale sulla parte che si muove**. Se la gamba sale qualche cm e poi torna indietro, il problema è quasi sempre qui.
- **Reset**: tieni premuto ▼ finché sul display sparisce "RST".
- **Ciclo di lavoro**: 2 minuti di funzionamento, 18 di pausa. Gli errori E01/E02 spesso si risolvono aspettando.
- Usare le gambe in verticale su un muro **non è un uso previsto dal produttore**: la garanzia potrebbe non coprirlo.

---

## Punti ancora aperti

- [ ] Posizione esatta dei 4 fori sulla testa delle gambe (per la piega della lastra).
- [ ] Posizione dei fori sui fianchi della scatola del motore (per la vaschetta delle staffe).
- [ ] Verifica della portata reale del muro.
- [ ] Peso finale del mobile pesato, non stimato.

---

## Sicurezza e responsabilità

Questo è un progetto amatoriale. **I calcoli sono stime, non sono stati verificati da un ingegnere strutturista**, e parte della progettazione è stata fatta con l'aiuto di un assistente AI.

- Un mobile di 60+ kg che si muove all'altezza della testa può fare **danni seri** se cede. Fai controllare struttura e ancoraggi da un professionista prima dell'uso.
- Il fissaggio dipende **interamente dal muro**: verificane il tipo e lo stato.
- Non montarlo dove possono arrivarci bambini senza supervisione; il piano aperto non è un appoggio per sedersi o salire.
- L'impianto elettrico interno va fatto a regola d'arte; se non sei sicuro, rivolgiti a un elettricista.

Il progetto è fornito **"così com'è"**, senza garanzie. Chi lo costruisce lo fa sotto la propria responsabilità.

---

## Ispirazione

Ispirato all'idea delle scrivanie a muro con ribalta e regolazione in altezza in commercio (come Wallrise e DropTop). Questo progetto **non è affiliato** a quei marchi e non ne riproduce disegni o componenti. FlexiSpot, Livenza, Meroni e gli altri marchi citati appartengono ai rispettivi proprietari.

---

## Licenza

Documentazione e disegni: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.it) — pubblico dominio. Puoi farne quello che vuoi, anche per uso commerciale, senza chiedere permesso e senza obbligo di citare l'autore. Testo completo nel file [LICENSE](LICENSE).
