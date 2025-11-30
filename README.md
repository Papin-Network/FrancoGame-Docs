# FrancoGame Docs
[![pages-build-deployment](https://github.com/Papin-Network/FrancoGame-Docs/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/Papin-Network/FrancoGame-Docs/actions/workflows/pages/pages-build-deployment)
Documentazione e materiali di supporto per i tester di FrancoGame (build interne). Qui trovi pagine statiche con istruzioni rapide per download, setup e uso dei comandi console.

## Struttura
- `beta-tester/index.html` – guida per i tester: comandi console, preset grafici, checklist bug e istruzioni per aprire issue su GitHub.
- `assets/` – fogli di stile, immagini e risorse condivise dalla guida.
- `.github/` – workflow/configurazioni di supporto.

## Come visualizzare
Apri `beta-tester/index.html` nel browser (doppio click da file system). La pagina include selettore di tema (chiaro/scuro/sistema) e navigazione laterale.

## Segnalazione bug
Segui la sezione 8 della guida:
1. Apri la repository di gioco su GitHub > Issues > New issue (non c'è template).
2. Titolo: area + problema (es. `[Cattedrale] FPS bassi nell'ingresso`).
3. Incolla la checklist (preset, comandi attivi, passi per riprodurre) e allega screenshot/video.
4. Etichette: `bug` in Labels, `Bug` in Type.

## Note
- Pensato per build interne UE 5.5.4, non condividere esternamente.
- Se mancano sezioni o servono integrazioni, aggiungi una sottosezione dedicata in `beta-tester/index.html`.
