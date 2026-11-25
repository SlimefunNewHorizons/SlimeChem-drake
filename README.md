<!-- credits:start -->
> **Credits & license.** Port and maintenance by [JackStar6677-1](https://github.com/JackStar6677-1) and [DrakesCraft Labs](https://github.com/SlimefunNewHorizons). Original authors: Seggan, Riley31415 and TheBusyBiscuit (contributors of the upstream [Slimefun-Addon-Community/SlimeChem](https://github.com/Slimefun-Addon-Community/SlimeChem)) and Mooy1 (plugin.yml authors). Upstream license: **GNU Lesser General Public License v3.0** (see [LICENSE](LICENSE)). Details: [docs/UPSTREAM_ATTRIBUTION.md](docs/UPSTREAM_ATTRIBUTION.md) · Policy: [Rights & Attribution](https://github.com/SlimefunNewHorizons/.github/blob/main/RIGHTS_AND_ATTRIBUTION.md). Independent community project, not affiliated with or endorsed by the original authors or the official Slimefun team.
>
> **Créditos y licencia.** Port y mantenimiento por [JackStar6677-1](https://github.com/JackStar6677-1) y [DrakesCraft Labs](https://github.com/SlimefunNewHorizons). Autores originales: Seggan, Riley31415 and TheBusyBiscuit (contributors of the upstream [Slimefun-Addon-Community/SlimeChem](https://github.com/Slimefun-Addon-Community/SlimeChem)) and Mooy1 (plugin.yml authors). Licencia original: **GNU Lesser General Public License v3.0**. Detalle en [docs/UPSTREAM_ATTRIBUTION.md](docs/UPSTREAM_ATTRIBUTION.md).
<!-- credits:end -->

> **Branches / Ramas.** `main`: Paper/Purpur 1.21.11 (Java 21). `port-26x`: Paper/Purpur 26.x (production: Purpur 26.2, Java 25). If another section of this README says otherwise, this note prevails. / Si otra seccion de este README dice otra cosa, prevalece esta nota.

> [!WARNING]
> **Experimental:** SlimeChem originated as an unfinished addon. This independent port runs on DrakesCraft, but its presence in production does not establish completeness, safety for every configuration, or endorsement by upstream. Test on a disposable server before using it elsewhere.
>
> Related upstream project and contributors: https://github.com/Slimefun-Addon-Community/SlimeChem. Upstream provenance and license notices are being reviewed.

<div align="center">

  <img src="https://raw.githubusercontent.com/SlimefunNewHorizons/SlimeChem-drake/main/banner.svg" alt="SlimeChem-drake Banner" width="920" />

# ⚡ SlimeChem — Drake Edition

**Experimental chemistry addon for Slimefun4 (Paper / Purpur 1.21.11 and 26.x)**

<p>
  <a href="https://github.com/SlimefunNewHorizons/SlimeChem-drake"><img src="https://img.shields.io/badge/GitHub-SlimeChem-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Slimefun4-Drake_Edition-22C55E?style=for-the-badge&logo=curseforge&logoColor=white" alt="Slimefun4"/>
  <img src="https://img.shields.io/badge/Paper%20%2F%20Purpur-1.21.11%20%7C%2026.2-38BDF8?style=for-the-badge&logo=minecraft&logoColor=white" alt="Paper / Purpur 1.21.11 and 26.2"/>
  <img src="https://img.shields.io/badge/Java-21%20%7C%2025-F89820?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21 and 25"/>
</p>

[🇬🇧 **English**](README.md) · [🇪🇸 **Español**](README_ES.md)

</div>

> ### 🏰 Join the Official DrakesCraft Community!
> 
> * 🎮 **Server IP**: `mc.drakescraft.cl` *(Java & Bedrock; Purpur 26.2, ports 25565 / 19132)*
> * 💬 **Official Discord**: [discord.gg/drakescraft](https://discord.gg/rv3vtXZTk7) — *Check out `#general-english`!*
> * 🌐 **Website & Guides**: [web.drakescraft.cl](https://web.drakescraft.cl) — 🛒 **Store**: [web.drakescraft.cl/store](https://web.drakescraft.cl/store.html)
> 
> *Play with this addon alongside 107 Slimefun addons live on our technical survival network!*

---

## 📖 What is SlimeChem?

**SlimeChem-drake** is a modular expansion within the **DrakesCraft Labs** ecosystem, ported and maintained for Minecraft **Paper / Purpur**: branch `main` targets 1.21.11 (Java 21) and branch `port-26x` targets 26.x (Java 25), the line that currently runs on the DrakesCraft production server (Purpur 26.2).

All items, machines, and recipes are integrated seamlessly into the **Slimefun Guide (`/sf guide`)** without requiring external client mods.

---

## ⚙️ Key Features & Systems

* **Performance and persistence:** Compatibility changes exist, but latency and loss-free recovery are not guaranteed and require independent testing.
* ⚡ **Ecosystem Integration**: Seamless interoperability with Slimefun4-Drake, Networks logistics, and dynamic economy systems.
* 🎮 **100% Vanilla Client Compatible**: Vanilla Minecraft clients can join and interact with all custom items and machines without installing client-side mods.

---

## 📋 Technical Compatibility

| Parameter | Requirement |
|---|---|
| **Server Software** | `main`: Paper / Purpur **1.21.11** · `port-26x` (production): Purpur / Paper **26.2** |
| **Java Runtime** | `main`: **Java 21** · `port-26x`: **Java 25** |
| **Required Core** | [Slimefun4-Drake](https://github.com/SlimefunNewHorizons/Slimefun4-Drake) |
| **Architecture** | 100% Server-Side (Vanilla Minecraft clients can join without installing client mods) |

---

## 📥 Installation

1. Download the latest release `.jar` from the [Releases](https://github.com/SlimefunNewHorizons/SlimeChem-drake/releases) tab or [Modrinth](https://modrinth.com/organization/drakescraft-labs).
2. Place the `.jar` into your server's `plugins/` directory alongside `Slimefun4-Drake.jar`.
3. Start or restart your server. Recipes and machines will appear automatically in the Slimefun guide (`/sf guide`).

---

## 🛠️ Building from Source

```bash
git clone https://github.com/SlimefunNewHorizons/SlimeChem-drake.git
cd SlimeChem-drake
mvn clean package -DskipTests
```

The compiled artifact will be located under `target/SlimeChem-drake.jar`.

---

<div align="center">

**Port maintained by [DrakesCraft Labs](https://github.com/SlimefunNewHorizons); original work by upstream contributors.**

</div>

---

## 📄 License & Upstream Attribution

This project is a sovereign fork maintained by [**JackStar6677-1**](https://github.com/JackStar6677-1) under [**DrakesCraft Labs**](https://github.com/SlimefunNewHorizons).

- **Related upstream project:** [Slimefun-Addon-Community/SlimeChem](https://github.com/Slimefun-Addon-Community/SlimeChem), whose plugin metadata credits Mooy1, Seggan and TheBusyBiscuit. Exact provenance is under review.
- **Changes:** See the commit history for port changes and dates. Concurrency, crash recovery and exploit resistance require independent validation.
- **License:** [GNU LGPL v3](LICENSE). Review upstream notices and applicable requirements before redistribution.
