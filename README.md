# EspadaWorld – Lineage II High Five Server
<img src="https://github.com/worldespada-cloud/trunk/blob/main/dist/gameserver/images/banner.png" width="100%"/>
EspadaWorld is a custom **Lineage II High Five** server project built on a customized L2J-style core, designed for private server development, gameplay customization, and production deployment.

The repository includes the core Java sources, datapack resources, server distribution files, protection-related modules, and web/community customizations used by the project.

---

## Overview

EspadaWorld extends a High Five server base with custom gameplay systems and administrative tooling, including features such as:

- Community Board custom systems
- Auction-related functionality
- Ranking systems
- Dress / Undress systems
- Custom PvP zone logic
- Protection module integration
- Datapack and server packaging scripts

This repository is intended for active development, maintenance, and deployment of the EspadaWorld game server environment.

---

## Repository Structure

The project is organized around the following major components:

- `java/` — core Java source code for login server, game server, shared systems, and custom features
- `dist/` — runtime distribution files, server data, scripts, HTML, configs, and libraries
- `builds/` — generated build artifacts
- `images/` — repository images and documentation assets
- `Jars.xml` — Ant build script for compiling and packaging server JARs
- `Datapack.xml` — Ant build/deployment script for datapack export and distribution
- `ProGuard*.pro` — obfuscation configuration files for release packaging

---

## Core Build Details

The project uses **Apache Ant** build scripts rather than a standard Maven/Gradle workflow.

The main packaging flow is handled through:

- `Jars.xml` — compiles Java sources and packages:
  - login server JAR
  - game server JAR
  - commons JAR
  - protect JAR
  - scripts JAR
- `Datapack.xml` — synchronizes and exports distribution content for deployment

The Java build configuration targets **Java 25** compatibility.

---

## Requirements

Before building or running the project, make sure your environment includes:

- **JDK 25+**
- **MySQL 5.6+**
- **Apache Ant**
- **Git LFS** (recommended for large binary assets)
- Windows or Linux environment capable of running the server stack

---


