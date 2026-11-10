# ClockV1-OTA

Mises à jour des horloges ClockV1 (ESP32, dalle HUB75).

- `version.json` : version disponible, firmware, MD5, fichiers de la SPIFFS à mettre à jour (`web/`) et fichiers obsolètes à supprimer.
- `Clock_Vx.xx.bin` : firmware.
- `web/` : page web (`index.html.gz`) et saints (`SaintN.json`).

Les horloges lisent ces fichiers via `raw.githubusercontent.com` (page Système → Mise à jour, ou automatiquement vers 3 h si activé).
`config.json` n'est jamais modifié.
