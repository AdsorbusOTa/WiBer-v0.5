> Aktuelle Version: **v0.5.0**
> [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/adsorbusota/wiber-app/branch/main/WiBer_v0-5.py)
# WiBer – Webtool zur Bewertung von Kältemaschinen

WiBer ist ein Streamlit-basiertes Tool zur Analyse von Kälteleistung, Energieeinsparung und wetterabhängigen Betriebsbedingungen.

## 🔧 Funktionen

- Eingabe von Kühlbedarf, Lastprofil und Temperaturdifferenz
- Automatischer Abruf von Außentemperaturdaten (DWD, über wetterdienst)
- Zählung von Stunden in Temperaturbereichen
- Vergleich mit Effizienzgrenzen
- Diagramm + Auswertung

## 🚀 Start

```bash
pip install -r requirements.txt
streamlit run WiBer_v0-5.py

## 📦 Abhängigkeiten

Dieses Projekt basiert auf folgenden zentralen Bibliotheken:

- streamlit
- wetterdienst (v0.107.0)
- geopy
- polars
- cryptography
- pandas

Die vollständige Liste ist in `requirements.txt` enthalten.
