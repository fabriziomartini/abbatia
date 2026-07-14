# Mappa illustrata del Casentino

`il-casentino.png` — mappa generata (Higgsfield / nano_banana_pro) in stile pergamena, coerente con la planimetria dell'Abbatīa già presente nella chat (`immagini-generate/IMG-20260319-WA0040.jpg`). Rappresenta la geografia fissata in `cronache/scenario.md`: l'Antica Abbatīa di San Gineprio sul passo tra Pratomagno e Monte Falterona, il villaggio di Cuccurano a valle, il Passo della Consuma verso Firenze, e il percorso di alcuni giorni verso il Lago di Equi Terme.

Testo interamente in italiano (corretto in una seconda generazione: la prima versione riportava "Travel path" in inglese).

## Planimetria dell'Abbatīa (da generare)

Da salvare come `planimetria.png` una volta generata. Prompt pronto (Higgsfield/nano_banana_pro o Gemini):

Prima versione (usata per generare `planimetria.png`): buona ortografia e stile piatto corretto, ma "Porcarium" scritto due volte (una con un possibile accento di troppo) e la Casa dell'Abate venuta piccola, non abbastanza separata.

Il tentativo v2 (troppo aggressivo su "freestanding two-story manor house") ha fatto scivolare il render verso una vista 3D isometrica invece di restare una planimetria piatta: scartato.

Prompt v3, corretto su entrambi i punti senza perdere lo stile piatto della v1:

```
Hand-illustrated antique parchment architectural floor plan (planimetria), sepia ink line work with light watercolor wash, same aged-manuscript engraving style as a medieval abbey ground plan: foxed vellum texture, ink hatching, simple decorative border with light corner flourishes, no crest, no coat of arms, clean and uncluttered. STYLE LOCK, most important rule: this must be a FLAT, TWO-DIMENSIONAL, TOP-DOWN ARCHITECTURAL FLOOR PLAN (blueprint style, walls seen directly from above as outlined shapes), exactly like a real building blueprint. Do NOT draw it as a 3D isometric view, do NOT draw it as an aerial bird's-eye illustration, do NOT show roof slopes, roof tiles or building height or a horizon or sky — flat plan only, as if traced from directly overhead.

CRITICAL SPELLING REQUIREMENT: every single word of text must be correct standard Italian, perfectly spelled, proofread mentally before rendering, absolutely zero English words, zero misspellings, zero stray accent marks on words that should not have any. Top title cartouche reads exactly 'ANTICA ABBATĪA DI SAN GINEPRIO' spelled letter by letter: capital A-N-T-I-C-A, then ABBAT, then a lowercase i with a single straight horizontal macron bar above it (never a capital I, never diaeresis dots), then A, then DI SAN GINEPRIO. Beneath it smaller: 'Planimetria'.

Orient the flat plan consistently with an existing regional map of the same abbey: the main gatehouse and entrance path face south-southwest (toward the bottom of the drawing), a fish pond sits just outside or against the eastern wall (right side of the drawing), dense forest borders the western and northern walls (left and top side), more open ground toward the east.

Label these rooms/areas with a small correctly-spelled Italian caption placed next to each one, each word appearing only ONCE on the whole map (proofread each one, especially: Chiesa Abbaziale, Chiostro, Biblioteca e Scriptorium, Refettorio, Cucina, Cantina, Cripta, Orto, Porcarium, Laghetto, Portineria): a large abbey church labeled 'Chiesa Abbaziale'; a covered arcaded cloister with a small central fountain labeled 'Chiostro'; a library/scriptorium room labeled 'Biblioteca e Scriptorium'; a dining hall labeled 'Refettorio'; a kitchen labeled 'Cucina'; a wine cellar labeled 'Cantina'; an underground crypt labeled 'Cripta'; a dormitory wing with three small individual monk's cell rooms, each with its own small correct label reading exactly 'Cella di Fra Martino', 'Cella di Fra Cordino', and 'Cella di Padre Pier Poulet' (proofread these three names very carefully, they are proper names); ONE single small pig enclosure only, appearing nowhere else on the map, labeled exactly 'Porcarium' spelled P-O-R-C-A-R-I-U-M with absolutely no accent mark on any letter; a vegetable garden on open ground near the eastern side labeled 'Orto'; a small pond with fish on the eastern side, just outside the wall, labeled 'Laghetto'; a gatehouse entrance on the south-southwest side, where a path leads away toward a distant village, labeled 'Portineria'; surrounding stone walls with corner towers and a fortified gate.

The abbot's residence: within the same walled abbey complex as everything else (not a separate building outside the walls, not in a different location on the map), draw a distinct room or small suite of rooms clearly larger than any single monk's cell, roughly 3 times the floor area of one cell, drawn as its own separate block with its own outline, set apart from the dormitory row of cells by a wall, corridor or small internal courtyard gap so it is visually obvious it is not one of the cells. Label it 'Casa dell'Abate Elfo'. Directly beside it, as its own smaller adjoining room with a separate outline, place a private chapel labeled 'Cappella Privata'. Still flat, top-down, same drawing style as the rest of the plan, no special 3D treatment for this building.

One single small compass rose in a corner labeled only 'N', 'S', 'E', 'O' (only one on the whole map). A small hand-drawn scale bar. Warm sepia, faded olive-grey and muted ochre watercolor tones only, aged paper stains, slightly torn edges, clean readable flat architectural blueprint style, elegant and uncluttered, not photorealistic, not a landscape map, not a 3D view.
```

