# EspadaWorld Reborn - Lineage 2 High Five Private Server

<img src="https://github.com/worldespada-cloud/EspadaWorld/blob/main/banner.png" width="100%" alt="EspadaWorld Reborn - Lineage 2 High Five Private Server" />

**EspadaWorld Reborn** is a cinematic **Lineage 2 High Five private server** project focused on balanced gameplay, intense PvP, immersive progression, custom systems, vote rewards, rankings, protection features, and stable production deployment.

The project is built around a customized L2J-style server core and includes the server sources, datapack resources, runtime distribution files, protection-related modules, admin tooling, vote integrations, custom instances, and web/community systems used by the EspadaWorld environment.

---

## Play EspadaWorld Reborn

EspadaWorld Reborn is designed for players who want a polished Lineage 2 High Five experience with a strong fantasy atmosphere, active progression systems, PvP competition, PvE content, custom zones, vote rewards, rankings, and community-driven gameplay.

- Official website: **https://l2espadaworld.com**
- Server chronicle: **Lineage 2 High Five**
- Project focus: **PvP, PvE, rankings, vote rewards, events, custom instances, protection systems, community systems, and long-term stability**

---

## Main Features

EspadaWorld extends a High Five server base with custom gameplay systems, administrative tooling, protection modules, vote integrations, and deployment support.

Main project areas include:

- Lineage 2 High Five private server core
- Custom Community Board systems
- Player ranking systems
- Unified vote reward system
- Multiple vote website integrations
- Custom PvP and gameplay logic
- Custom Espada instance and PvE content
- Auction-related functionality
- Dress / undress systems
- Protection module integration
- Admin tools and server management systems
- Datapack and server packaging scripts
- Web and community customization support

This repository is intended for active development, maintenance, presentation, and deployment of the EspadaWorld game server environment.

---

## Vote Reward System

EspadaWorld includes a custom vote reward flow designed around a unified `.getreward` command.

The system can verify votes from multiple vote websites and reward the player only after all enabled vote links are confirmed. This allows the server to use a single global reward configuration instead of separate rewards for each vote website.

Supported vote-related functionality includes:

- Unified `.getreward` command
- Multiple vote website checks
- Global vote reward configuration
- Individual vote confirmation logic
- Cooldown / reuse protection
- HWID / IP-based reward protection
- Debug logging for vote verification
- Configurable reward items, amounts, and chances

---

## Protection Systems

The project includes protection-related modules and integration points for server/client security workflows.

Protection-related work in EspadaWorld focuses on:

- Runtime protection module integration
- Client protection support
- Server-side validation systems
- Anti-abuse logic around vote rewards and account actions
- Configuration-driven security behavior
- Release packaging support for protected builds

Protection details, private keys, sensitive production configuration, and deployment-specific security data should always remain outside public commits.

---

## Custom Gameplay Content

EspadaWorld Reborn includes custom gameplay systems designed to give the server its own identity while keeping the Lineage 2 High Five foundation.

Examples of custom content and systems:

- Custom Espada instance
- PvP-focused systems and zones
- PvE progression support
- Ranking and competition systems
- Community Board extensions
- Vote reward progression
- Custom HTML and datapack content
- Gameplay scripts and server-side feature extensions

---

## Repository Structure

The project is organized around the following major components:

- `java/` - core Java source code for login server, game server, shared systems, scripts, and custom features
- `dist/` - runtime distribution files, server data, scripts, HTML, configs, libraries, and deployment resources
- `builds/` - generated build artifacts
- `images/` - repository images and documentation assets
- `Jars.xml` - Apache Ant build script for compiling and packaging server JARs
- `Datapack.xml` - Apache Ant build/deployment script for datapack export and distribution
- `ProGuard*.pro` - obfuscation configuration files for release packaging

---

## Core Build Details

The project uses **Apache Ant** build scripts rather than a standard Maven or Gradle workflow.

The main packaging flow is handled through:

- `Jars.xml`, which compiles Java sources and packages:
  - login server JAR
  - game server JAR
  - commons JAR
  - protect JAR
  - scripts JAR
- `Datapack.xml`, which synchronizes and exports distribution content for deployment

The Java build configuration targets **Java 25** compatibility.

---

## Requirements

Before building or running the project, make sure the environment includes:

- **JDK 25+**
- **MySQL 5.6+**
- **Apache Ant**
- **Git LFS** recommended for large binary assets
- Windows or Linux environment capable of running the server stack

---

## SEO Keywords

Lineage 2 High Five server, Lineage 2 private server, L2 High Five private server, Lineage 2 PvP server, L2 server play now, EspadaWorld Reborn, Espada World, vote rewards, rankings, custom Lineage 2 instance, High Five server, L2 H5 2026.

---

## Project Status

EspadaWorld Reborn is under active development and maintenance. The project continues to evolve with gameplay improvements, server-side optimizations, website features, vote integrations, protection updates, custom instances, and deployment refinements.

---

## Note

This repository is used as a public presentation and development repository for the EspadaWorld Reborn project. Deployment-specific configuration, credentials, private protection details, production keys, and sensitive server data should always remain outside public commits.
