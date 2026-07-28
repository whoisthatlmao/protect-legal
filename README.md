# 🛡️ Protect Bot — Discord Security & Moderation All-in-One

<p align="center">
  <img src="https://img.shields.io/badge/Discord.py-v2.x-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord.py">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/License-CGU%20%26%20Privacy-green?style=for-the-badge" alt="License">
</p>

**Protect** est un bot de sécurité tout-en-un puissant, moderne et 100% gratuit pour Discord. Il protège activement votre serveur contre les raids, les spams, les nukes et les comportements malveillants tout en offrant un dashboard Web interactif et des outils complets de modération et de gestion de communauté.

---

## 🔗 Liens Utiles & Légaux

- 📜 **<a href="https://whoisthatlmao.github.io/protect-legal/" target="_blank" rel="noopener noreferrer">Conditions Générales d'Utilisation (CGU) & Politique de Confidentialité</a>**
- 🌐 **Dashboard Web** : Inclus dans le projet (Flask & Tailwind/Modern UI)

---

## ✨ Fonctionnalités Principales

### 🛡️ Sécurité & Anti-Nuke
- **Anti-Nuke Avancé** : Protection automatique contre la suppression massive de salons, rôles ou bannissements suspects.
- **Anti-Raid & Anti-Spam** : Détection intelligente des joins massives, des répétitions de messages, liens non autorisés et spams de mentions.
- **Anti-GhostPing** : Détection et sanction des pings invisibles / rapides.
- **Filtre de Mots Interdits (Badwords)** : Modération automatique du vocabulaire avec système d'avertissements et de mutes.

### 🔨 Modération Moderne
- **Sanctions complètes** : `/ban`, `/unban`, `/kick`, `/mute`, `/unmute`, `/warn`, `/clear` (purge).
- **Modération Avancée & Blacklist** : Gestion fine de la liste noire des utilisateurs et des permissions de modération.
- **Journaux de Modération (Logs)** : Audit détaillé et exportable de toutes les actions réalisées sur le serveur.

### 🎟️ Tickets, Vérification & Bienvenue
- **Système de Vérification** : Filtrage des nouveaux membres via boutons ou captchas avant de donner l'accès au serveur.
- **Système de Tickets** : Création et gestion complète de tickets de support avec transcriptions.
- **Message de Bienvenue / Au revoir** : Messages personnalisables avec cartes graphiques et rôles automatiques.

### 🌐 Dashboard Web & Sauvegardes
- **Dashboard en temps réel** : Configurez votre bot directement depuis votre navigateur avec une interface moderne.
- **Système de Backup** : Sauvegardez et restaurez la structure de vos salons, rôles et configurations en un instant.

---

## 🛠️ Stack Technique

- **Langage** : Python 3.10+
- **Bibliothèque Bot** : `discord.py`
- **Dashboard** : Flask, Jinja2, HTML5 / CSS3 (Design moderne)
- **Base de Données** : MongoDB (Motor async)
- **Hébergement supporté** : Discloud, Railway, Heroku / Docker (Procfile & discloud.config inclus)

---



---

## 📋 Commandes Principales

| Commande | Description | Permission |
| :--- | :--- | :--- |
| `/help` | Affiche le menu d'aide interactif du bot | Tous |
| `/config` | Ouvre le menu de configuration du serveur | Administrateur |
| `/setup` | Guide de configuration rapide | Administrateur |
| `/ban [membre] [raison]` | Bannit un utilisateur du serveur | Ban Members |
| `/kick [membre] [raison]` | Expulse un utilisateur | Kick Members |
| `/mute [membre] [durée]` | Règle le timeout/mute d'un utilisateur | Moderate Members |
| `/warn [membre] [raison]` | Avertit un utilisateur | Moderate Members |
| `/clear [nombre]` | Supprime un nombre spécifique de messages | Manage Messages |
| `/ticket setup` | Installe le panneau de ticket dans un salon | Administrateur |
| `/verify setup` | Installe le système de vérification des membres | Administrateur |
| `/backup create` | Crée une sauvegarde du serveur | Propriétaire |

---

## ⚖️ Mentions Légales & CGU

En utilisant ou en hébergeant **Protect**, vous acceptez nos Conditions Générales d'Utilisation et notre Politique de Confidentialité. 

Pour consulter les informations complètes sur le traitement des données et les CGU, visitez la page dédiée :
👉 **<a href="https://whoisthatlmao.github.io/protect-legal/" target="_blank" rel="noopener noreferrer">https://whoisthatlmao.github.io/protect-legal/</a>**

---

<p align="center">
  Fait avec ❤️ par <b>ad44/b> — Protect Security Team
</p>
