FishPilot V0.19 – Oberried Master-Strukturkatalog

Produktive Dateien:
- index.html
- bathymetry.geojson
- fishpilot_structures_oberried_v019.geojson
- fishpilot_area_oberried_v019.geojson
- fishpilot_catch_schema_v01.json

V0.19:
- 15 bestehende Oberried-Strukturen in einen permanenten Masterkatalog überführt.
- Einheitliche Strukturtypen und Marker: K = Kante, N = Nase, R = Rinne, P = Plateau, RÜ = Rücken.
- Permanente IDs: OBR-Kxx, OBR-Nxx, OBR-Rxx, OBR-Pxx, OBR-RUxx.
- legacy_id bewahrt die bisherige V0.18-ID zur Rückverfolgbarkeit.
- GPS-Navigation und Filter bleiben erhalten.
- separates Fischereigebiet OBR als Grundlage für spätere Gebietsauswahl.

WICHTIG:
Das Gebietspolygon ist in V0.19 zunächst eine technische Arbeitsgrenze um den vorhandenen Oberried-Katalog.
Vor der Ausweitung auf weitere Gebiete sollte die fachlich gewünschte Ufergrenze final festgelegt werden.

Nächster Entwicklungsschritt:
Fangkatalog/Session-Log mit Struktur-ID, Nullfang-Sessions, Methode/Köder sowie Wetter- und Wasserdaten.


V0.19.1
- Gebiet Oberried räumlich bereinigt.
- Vier klar abgesetzte südöstliche/offshore Strukturen aus dem Oberried-Katalog entfernt.
- Entfernte IDs: OBR-K01, OBR-N02, OBR-P01, OBR-P03


V0.20
- Oberried auf 8 zusammenhängende Hotspots bereinigt.
- Entfernte isolierte südöstliche Strukturen: OBR-K03, OBR-K04, OBR-P04
- Fangjournal V0.2 vorbereitet.
- Fang/Nullfang, Fischart, Methode, Köder, Angeltiefe, Länge und Notiz erfassbar.
- Speicherung zunächst lokal im Browser (kein Server/Account erforderlich).
- Wetter- und Wasserdatenfelder für spätere API-Anbindung vorbereitet.
