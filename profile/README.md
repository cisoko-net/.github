<div align="center">

<h1>Cisoko</h1>

<a href="https://cisoko.net"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=D8A83E&center=true&vCenter=true&width=560&lines=Open+FiveM+foundations;One+bridge+for+ESX%2C+QBCore+and+Qbox;SQLite+inside+FXServer;Optimized+down+to+the+core" alt="Open FiveM foundations" /></a>

<p>
<a href="https://cisoko.net"><img src="https://img.shields.io/badge/Store-cisoko.net-D8A83E?style=for-the-badge&labelColor=090909" alt="Store" /></a>
<a href="https://cisoko.net/docs"><img src="https://img.shields.io/badge/Docs-read-D8A83E?style=for-the-badge&labelColor=090909" alt="Docs" /></a>
<a href="https://discord.cisoko.net"><img src="https://img.shields.io/badge/Discord-join-D8A83E?style=for-the-badge&logo=discord&logoColor=FFE08A&labelColor=090909" alt="Discord" /></a>
</p>

</div>

**Cisoko** makes FiveM resources for roleplay servers, shipping since 2021.

These are the foundations every Cisoko resource stands on. They are free to
use, and each one runs on ESX, QBCore and Qbox.

### Repos

| | Repo | What it does |
|---|---|---|
| 📚 | [**cis_libs**](https://github.com/cisoko-net/cis_libs) | Base library that every Cisoko resource loads. |
| 🔌 | [**cis_bridge**](https://github.com/cisoko-net/cis_bridge) | One set of exports for money, items, jobs, doors and targets, with an adapter per framework and inventory. |
| 🗄️ | [**cis_database**](https://github.com/cisoko-net/cis_database) | SQLite inside FXServer that provides `oxmysql`, with a MariaDB replica. |

### How we build

- The server decides. Money, items, jobs and positions are checked server-side.
- Idle resmon stays at 0.00–0.02 ms.
- Every fix ships with a test that failed first.
- No framework forks, no obfuscated dependencies, no remote code loading.

### Stack

<img src="https://skillicons.dev/icons?i=lua,ts,js,vite,nodejs,mysql,sqlite,cloudflare,linux,git&theme=dark" alt="Lua, TypeScript, JavaScript, Vite, Node.js, MySQL, SQLite, Cloudflare, Linux, Git" />

Bug reports go to each repo's issues. Questions go to [Discord](https://discord.cisoko.net).

<div align="center">
<sub>Cyprus · since 2021</sub>
</div>
