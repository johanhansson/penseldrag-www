# penseldrag-www

Förrenderade målningar till Home Assistant-korten `panna-penseldrag-card` och `element-penseldrag-card` (Värme → Bild). Home Assistant hämtar filerna med integrationen Downloader till `/config/www/penseldrag/`, och korten visar dem direkt i stället för att måla med p5.js + p5.brush i webbläsaren.

| Fil | Kort | Storlek |
|---|---|---|
| `panna-scen-1.webp` | `panna-penseldrag-card` 1.1.0 | 1560×1040 |
| `element-scen-1.webp` | `element-penseldrag-card` 1.1.0 | 1840×1440 |

Bilderna är det statiska, penselmålade lagret (papper, tank, panna, hus, rum, element, rör). Färger efter temperatur, texter och animationer ritas ovanpå i webbläsaren. Siffran i filnamnet ökas när målningen ändras, så att webbläsarens cache inte visar en gammal bild.

Dokumentation och beslut: privata repot `johanhansson/homeassistant`, `docs/notes/2026-10-25-penseldrag-forrenderat/`.
