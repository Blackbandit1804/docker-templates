# 🧩 Docker-Templates – Unraid (manuelle Installation)

![Docker Pulls](https://img.shields.io/docker/pulls/blackbandit1804/teamspeak-mariadb?style=for-the-badge&logo=docker)
![Image Size](https://img.shields.io/docker/image-size/blackbandit1804/teamspeak-mariadb/latest?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Blackbandit1804/docker-templates?style=for-the-badge&logo=github)

Vorlagen-Repository für **Unraid DockerMan**.

> **Hinweis:** In Unraid 7.x gibt es die frühere UI-Option „Template Repositories“ nicht mehr (deprecation).  
> Verwende stattdessen **Benutzer‑Vorlagen**: Lege die XML direkt unter `/boot/config/plugins/dockerMan/templates-user/` ab.

---

## 🇩🇪 Deutsch

### 🧩 Installation (ohne Community Apps)
Füge die TeamSpeak‑Vorlage lokal hinzu:
```bash
mkdir -p /boot/config/plugins/dockerMan/templates-user
curl -fsSL "https://raw.githubusercontent.com/Blackbandit1804/docker-templates/main/TeamSpeak3-MariaDB.xml"   -o /boot/config/plugins/dockerMan/templates-user/TeamSpeak3-MariaDB.xml
```
Danach in der WebUI: **Docker → Container hinzufügen → Vorlage auswählen → „TeamSpeak3-MariaDB“**.

### 🔗 Nützliche Links
- 🐳 **Docker Hub:** <https://hub.docker.com/r/blackbandit1804/teamspeak-mariadb>
- 💾 **GitHub (Build-Repo):** <https://github.com/Blackbandit1804/ts3-mariadb>
- 🧱 **Basis-Projekt:** <https://github.com/ich777/docker-teamspeak>

---

## 🇬🇧 English

### 🧩 Installation (without Community Apps)
Add the TeamSpeak template locally:
```bash
mkdir -p /boot/config/plugins/dockerMan/templates-user
curl -fsSL "https://raw.githubusercontent.com/Blackbandit1804/docker-templates/main/TeamSpeak3-MariaDB.xml"   -o /boot/config/plugins/dockerMan/templates-user/TeamSpeak3-MariaDB.xml
```
Then in the web UI: **Docker → Add Container → Select template → “TeamSpeak3-MariaDB”**.

### 🔗 Useful Links
- 🐳 **Docker Hub:** <https://hub.docker.com/r/blackbandit1804/teamspeak-mariadb>
- 💾 **GitHub (build repo):** <https://github.com/Blackbandit1804/ts3-mariadb>
- 🧱 **Base project:** <https://github.com/ich777/docker-teamspeak>

---

🧩 **Maintainer:** [Blackbandit1804](https://github.com/Blackbandit1804)  
📅 Getestet auf **Unraid 7.1.4**
