<h1 align="center">🚆 Sledovač Zpoždění Vlaků České Dráhy - Bílina 🚆</h1>

<p align="center">
  <a href="https://github.com/Sap1k/delayTracker_CzechRail">
    <img src="https://img.shields.io/badge/Original-Repository-blue?style=flat-square" alt="Original Repo">
  </a>
  <a href="https://github.com/odjezdy-online/ceskedrahy-delaytracker">
    <img src="https://img.shields.io/badge/Modified%20by-Me-brightgreen?style=flat-square" alt="Modified by Me">
  </a>
</p>

<h2 align="center">🚂 Hlavní Funkce</h2>

<ul>
  <li>**Domovská Stránka** - Přehledné rozhraní s hlavními informacemi a navigací</li>
  <li>**Sledování Odjezdů** - Automatické stahování dat o zpožděních každou minutu</li>
  <li>**Historie Vlaků** - Zobrazení historie zpoždění pro jednotlivé vlaky</li>
  <li>**Informace o Nástupištích** - Aktuální data o nástupištích pro každý vlak</li>
  <li>**API Rozhraní** - Možnost získat informace o vlacích programově</li>
  <li>**Databázové Ukládání** - Všechna data jsou ukládána do SQLite databáze</li>
</ul>

<h2 align="center">📦 Technologie</h2>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/APScheduler-blue?style=for-the-badge" alt="APScheduler">
</p>

<h2 align="center">📦 Instalace</h2>

<ol>
  <li><strong>Naklonujte repozitář:</strong>
    <pre><code>git clone https://github.com/odjezdy-online/ceskedrahy-delaytracker.git</code></pre>
  </li>
  <li><strong>Nainstalujte potřebné Python balíčky:</strong>
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li><strong>Spusťte aplikaci:</strong>
    <pre><code>python app.py</code></pre>
  </li>
</ol>

<p align="center">
  Aplikace bude dostupná na adrese <code>http://localhost:5010/</code>
</p>

<h2 align="center">📍 Navigace</h2>

<ul>
  <li>**/** - Domovská stránka s přehledem a navigací</li>
  <li>**/odjezdy** - Aktuální odjezdy a zpoždění vlaků</li>
  <li>**/historie** - Historie zpoždění jednotlivých vlaků</li>
</ul>

<h2 align="center">⚙️ Konfigurace Stanice</h2>

<p>- Výchozí stanice je nastavena na Bílina.></p>
<p>Číslo stanice, z které chcete monitorovat vlaky, lze jednoduše změnit úpravou API požadavku.</p>

<ol>
  <li>Navštivte <a href="https://www.cd.cz/stanice/">stránku stanic Českých drah</a>.</li>
  <li>Do vyhledávacího pole zadejte požadovanou stanici.</li>
  <li>Po výběru stanice se v URL objeví její číslo. Například pro stanici Děčín je URL <code>https://www.cd.cz/stanice/decin-hl-n-/5455659</code>, kde <strong>5455659</strong> je číslo stanice.</li>
  <li>V kódu aplikace změňte hodnotu <code>API_URL</code> podle čísla vaší stanice:</li>
</ol>

<h2 align="center">📝 Logování</h2>

<ul>
  <li>Aplikace automaticky loguje všechny příchozí požadavky</li>
  <li>Logy obsahují IP adresy a časové značky</li>
  <li>Soubory logů: <code>app.log</code> a <code>app.log.1</code></li>
</ul>

<h2 align="center">🤝 Přispívání</h2>

<p>
  Příspěvky jsou vítány! Pokud chcete přispět k vývoji:
</p>

<ol>
  <li>Forkněte repozitář</li>
  <li>Vytvořte novou větev pro vaše změny</li>
  <li>Commitněte vaše změny</li>
  <li>Vytvořte Pull Request</li>
</ol>

<h2 align="center">📄 Licence</h2>

<p align="center">
  Tento projekt je licencován pod <a href="https://opensource.org/licenses/MIT">MIT licencí</a>.
</p>

<h2 align="center">🤭💰 Donate</h2>

<p align="center">
  <a href="https://ko-fi.com/N4N225KML">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="ko-fi">
  </a>
  <a href="https://paypal.me/mxnticek">
    <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" alt="Donate with PayPal">
  </a>
</p>

<p align="center">
  Vytvořeno s ❤️ pro cestující České dráhy.
</p>
