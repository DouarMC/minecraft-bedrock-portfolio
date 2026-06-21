# Minecraft Bedrock Dev Portfolio

Hey, I'm a Bedrock developer and content creator focusing on the **Scripting API**, **Custom Components**, and clean addon architecture. 

I've been publishing tools and gameplay addons for a while, accumulating **over 300,000 total downloads** across my projects. This repo serves as a technical portfolio to showcase my coding standards and how I build optimized content for the Bedrock ecosystem.

---

## 🎮 Testing the Addons
If you want to test these projects directly in-game, you can download the ready-to-use `.mcaddon` files from the **[Releases Section](https://github.com/DouarMC/minecraft-bedrock-portfolio/releases)**.

---

## 🛠️ Tooling & Workflow Optimization
* **Custom VS Code Extension (WIP):** To speed up my workflow, I'm currently developing a VS Code extension designed to automate boilerplate generation for manifests, components, and Scripting API structures. It's an experimental internal tool aimed at moving concepts to production much faster.

---

## 📂 Featured Projects

### 1. More TNT (150K+ Downloads)
* **What it is:** A highly successful sandbox addon featuring 5 custom explosive types and throwable dynamites. 
* **Tech focus:** Built with Custom Components and server-side scripting, optimized to handle large-scale detonations without crashing game performance (TPS).
* **Code:** Located in the `/more-tnt` submodule.

### 2. Display Player & Mob Health (53K+ Downloads)
* **What it is:** A technical utility that renders real-time entity health text smoothly above their headers.
* **Tech focus:** Fully event-driven using the Scripting API (`entityHurt`, health listeners) and dynamic UI components. Optimized for multiplayer environments with high entity counts.
* **Code:** Located in the `/display-player-and-mob-health` submodule.

### 3. Team Manager (Active Project)
* **What it is:** A management utility allowing players to create, join, and manage teams/factions directly in-game.
* **Tech focus:** Heavily utilizes `@minecraft/server-ui` for complex form menus and relies on World Dynamic Properties for persistent multi-session data storage.
* **Code:** Located in the `/team-manager` submodule.

---

## 🚀 More Projects
This portfolio only highlights my top 3 technical projects. I have developed and maintained several other tools and expansions for the Bedrock community. You can check out my full catalog of released projects directly on my **[CurseForge Profile](https://www.curseforge.com/members/douarmc/projects)**.
