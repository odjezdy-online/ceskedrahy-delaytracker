
# České Dráhy Delay Tracker

Aplikace **České Dráhy Delay Tracker** slouží k monitorování zpoždění vlaků Českých drah. Pravidelně stahuje data z API a ukládá informace o vlacích do SQLite databáze, včetně zpoždění, nástupišť a skutečných časů příjezdů.

## Funkce

- Automatické stahování dat o zpoždění vlaků z API Českých drah každou minutu.
- Ukládání informací o vlacích, včetně plánovaných příjezdů, zpoždění a nástupišť, do SQLite databáze.
- API pro získání nástupiště konkrétního vlaku podle jeho čísla.
- Zobrazení historie zpoždění jednotlivých vlaků.
- Logování příchozích požadavků, včetně IP adresy.

## Instalace

1. Naklonujte tento repozitář:

   ```bash
   git clone https://github.com/uzivatel/ceskedrahy-delaytracker.git
   ```

2. Nainstalujte potřebné Python balíčky:

   ```bash
   pip install -r requirements.txt
   ```

3. Spusťte aplikaci:

   ```bash
   python app.py
   ```

Aplikace poběží na `http://localhost:5010/`.

## Úprava čísla stanice

Číslo stanice, z které chcete monitorovat vlaky, lze jednoduše změnit úpravou API požadavku.

1. Navštivte [stránku stanic Českých drah](https://www.cd.cz/stanice/).
2. Do vyhledávacího pole zadejte požadovanou stanici.
3. Po výběru stanice se v URL objeví její číslo. Například pro stanici Děčín je URL `https://www.cd.cz/stanice/decin-hl-n-/5455659`, kde **5455659** je číslo stanice.
4. V kódu aplikace změňte hodnotu `API_URL` podle čísla vaší stanice:

   ```python
   API_URL = 'https://www.cd.cz/stanice/5455659/getopt'
   ```

Tímto způsobem můžete sledovat vlaky z jakékoli stanice.

## Technologie

- Python
- Flask
- SQLite
- APScheduler
- Requests

## Původní práce

Původní práce je k dispozici na [GitHubu](https://github.com/Sap1k/delayTracker_CzechRail). Zbytek byl upraven mnou a z části také ChatGPT 4o/4o-mini.

## Licence

Tento projekt je licencován pod MIT licencí.
