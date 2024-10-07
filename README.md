<h1 align="center">🚆 České Dráhy Delay Tracker 🚆</h1>


<p align="center">
  <a href="https://github.com/Sap1k/delayTracker_CzechRail">
    <img src="https://img.shields.io/badge/Original-Repository-blue?style=flat-square" alt="Original Repo">
  </a>
  <a href="https://github.com/odjezdy-online/ceskedrahy-delaytracker">
    <img src="https://img.shields.io/badge/Modified%20by-Me-brightgreen?style=flat-square" alt="Modified by Me">
  </a>
</p>

<h2 align="center">✨ Funkce</h2>

<ul>
  <li>⏱️ <strong>Automatické stahování</strong> dat o zpoždění vlaků z API Českých drah každou minutu.</li>
  <li>💾 <strong>Ukládání informací o vlacích</strong>, včetně plánovaných příjezdů, zpoždění a nástupišť, do SQLite databáze.</li>
  <li>🚉 <strong>API</strong> pro získání nástupiště konkrétního vlaku podle jeho čísla.</li>
  <li>📊 <strong>Zobrazení historie zpoždění</strong> jednotlivých vlaků.</li>
  <li>📝 <strong>Logování</strong> příchozích požadavků, včetně IP adresy.</li>
</ul>

<h2 align="center">⚙️ Instalace</h2>

<ol>
  <li><strong>Naklonujte</strong> tento repozitář:
    <pre><code>git clone https://github.com/odjezdy-online/ceskedrahy-delaytracker.git</code></pre>
  </li>
  <li><strong>Nainstalujte</strong> potřebné Python balíčky:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li><strong>Spusťte</strong> aplikaci:
    <pre><code>python app.py</code></pre>
  </li>
</ol>

<p align="center">
  Aplikace poběží na <code>http://localhost:5010/</code>.
</p>

<h2 align="center">🚏 Úprava čísla stanice</h2>

<p>
  Číslo stanice, z které chcete monitorovat vlaky, lze jednoduše změnit úpravou API požadavku.
</p>

<ol>
  <li>Navštivte <a href="https://www.cd.cz/stanice/">stránku stanic Českých drah</a>.</li>
  <li>Do vyhledávacího pole zadejte požadovanou stanici.</li>
  <li>Po výběru stanice se v URL objeví její číslo. Například pro stanici Děčín je URL <code>https://www.cd.cz/stanice/decin-hl-n-/5455659</code>, kde <strong>5455659</strong> je číslo stanice.</li>
  <li>V kódu aplikace změňte hodnotu <code>API_URL</code> podle čísla vaší stanice:
    <pre><code>API_URL = 'https://www.cd.cz/stanice/5455659/getopt'</code></pre>
  </li>
</ol>

<h2 align="center">📜 Licence</h2>

<p align="center">
  Tento projekt je licencován pod <a href="https://opensource.org/licenses/MIT">MIT licencí</a>.
</p>

## ✨ Funkce

- ⏱️ **Automatické stahování** dat o zpoždění vlaků z API Českých drah každou minutu.
- 💾 **Ukládání informací o vlacích**, včetně plánovaných příjezdů, zpoždění a nástupišť, do SQLite databáze.
- 🚉 **API** pro získání nástupiště konkrétního vlaku podle jeho čísla.
- 📊 **Zobrazení historie** zpoždění jednotlivých vlaků.
- 🔐 **Logování** příchozích požadavků, včetně IP adresy.

## 📦 Technologie

- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
- ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
- ![APScheduler](https://img.shields.io/badge/APScheduler-blue?style=for-the-badge)


## 🤭💰 Donate
[Ko-Fi.com](https://ko-fi.com/vlastimilnovotny)
[PayPal.Me](https://paypal.me/mxnticek)