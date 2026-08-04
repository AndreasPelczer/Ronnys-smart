# Ronny's Smart Repair — Website

Statische One-Page-Website (ein `index.html`, komplett selbst-enthalten) für
**Ronny's Smart Repair**, Ronny Garn, Dürre Wiese 5, 97837 Erlenbach.
Service rund um Ihr Fahrzeug: Kleinlackierungen, Hagelschaden, Brandloch,
Felgen- & Fahrzeugaufbereitung, Parkdellen.

## Aufbau

```
index.html          Startseite (Hero, Leistungen + Fotos, Vorher/Nachher-Slider,
                    Smart-Repair-Erklärung, Ablauf, Anfahrt/Karte, Kontaktformular)
impressum.html      Impressum-Vorlage (§5 DDG)
datenschutz.html    Datenschutz-Vorlage (DSGVO)
assets/img/         Stockfotos (lokal, nicht gehotlinkt)
```

Kein Build, kein Framework, keine externen Requests beim Laden.
Deploy wie die anderen Cloudflare-Sites: Ordner hochladen, fertig.

## Noch zu erledigen (vor Livegang)

- [ ] **Impressum**: Rechtsform, USt-IdNr./Steuernr., ggf. Handwerkskammer eintragen (⚠︎-Stellen).
- [ ] **Datenschutz**: Hosting-Provider + Stand-Datum eintragen (⚠︎-Stellen), juristisch prüfen lassen.
- [x] **Echtes Logo** von Ronny eingebaut (`assets/img/logo.png` + beschnitten `logo-trim.png`).
- [ ] **Echte Vorher/Nachher-Fotos** von Ronny in den Slider (`assets/img/vorher-nachher.jpeg` ersetzen; ideal: dieselbe Stelle vorher/nachher).
- [ ] Optional: exakte **Geo-Koordinaten** für den Karten-Pin.
- [ ] Prüfen: Aussage „bis zu 70 % günstiger" mit Ronny abstimmen.

## Fotos / Lizenz

Alle Fotos in `assets/img/` von **Pexels** (Pexels-Lizenz: kostenlos, auch kommerziell,
keine Namensnennung nötig). Platzhalter, bis Ronnys eigene Fotos da sind.

| Datei | Motiv | Quelle |
|-------|-------|--------|
| lackierung.jpeg | Lackierpistole | pexels.com/photo/6870314 |
| politur.jpeg | Politur Motorhaube | pexels.com/photo/14908957 |
| polster.jpeg | Sitzreinigung | pexels.com/photo/5233285 |
| felgen.jpeg | Alufelge | pexels.com/photo/17110820 |
| innenraum.jpeg | Innenraum | pexels.com/photo/5288724 |
| detailing.jpeg | Detailing-Spray | pexels.com/photo/12920558 |
| vorher-nachher.jpeg | Politur (B/A-Demo) | pexels.com/photo/5233259 |
