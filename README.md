# 👨‍💻 Killian Van Ruymbeke

### Cybersécurité • DevSecOps • Automatisation d’infrastructure

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=26&duration=3200&pause=900&color=8D28F5&center=true&vCenter=true&width=900&lines=Cybersécurité+%26+DevSecOps;Automatisation+d'infrastructure;Sécurité+Cloud+%26+Containers;Création+de+plateformes+de+sécurité;Open+Source+%26+Cybersécurité+pratique" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://passandsecure.fr">
    <img src="https://img.shields.io/badge/Site-Pass%20And%20Secure-E040FB?style=for-the-badge" />
  </a>
  <a href="https://kvrcybertechno.fr">
    <img src="https://img.shields.io/badge/CV-En%20ligne-1B1035?style=for-the-badge" />
  </a>
  <a href="https://getgophishfr.com" style="text-decoration:none;">
    <img src="https://img.shields.io/badge/GophishFR-555555?style=for-the-badge"/>
    <img src="https://getgophishfr.com/images/badge-gophishfr-black.svg" height="28" style="vertical-align:middle;margin-left:-4px;"/>
  </a>
</p>

---

# 🧠 À propos

Passionné par la **cybersécurité**, le **DevSecOps** et l’**automatisation d’infrastructure**, je construis des outils et plateformes techniques orientés sécurité, fiabilité et déploiement reproductible.

Mon objectif est de rapprocher le développement, l’infrastructure et la cybersécurité pour concevoir des solutions **maintenables, automatisées et sécurisées dès la conception**.

Mes domaines principaux :

- 🛡️ Cybersécurité défensive & offensive
- ⚙️ DevSecOps & automatisation
- ☁️ Sécurité Cloud & Infrastructure as Code
- 🐳 Sécurité des containers
- 🔐 Hardening Linux / Active Directory
- 📦 Supply Chain Security
- 🤖 CI/CD, scripting et outillage interne

J’aime construire des **projets open source concrets**, expérimenter de nouvelles architectures, documenter mes apprentissages et créer des outils réellement utilisables.

---

# 🧰 Stack & outils

<p align="center">
  <img src="https://img.shields.io/badge/Linux-1B1035?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-8D28F5?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-1B1035?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-8D28F5?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-1B1035?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-8D28F5?style=for-the-badge&logo=powershell&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-1B1035?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-8D28F5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-1B1035?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-8D28F5?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-1B1035?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-8D28F5?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/React-1B1035?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-8D28F5?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-1B1035?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

---

# 🚀 Projets principaux

## 🧠 Mnemo

Assistant local-first d’historique shell développé en **Rust**, pensé pour retrouver rapidement ses commandes via une **TUI moderne**, une recherche fuzzy et un contexte projet basé sur Git.

Mnemo enregistre l’historique dans une base **SQLite locale**, sans serveur ni cloud, avec une approche orientée confidentialité, fiabilité et sécurité dès la conception.

Ce projet me permet de démontrer une approche complète **DevSecOps / Security by Design** appliquée à un outil réel :

- 🦀 **Rust & robustesse logicielle** : binaire unique, typage fort, gestion stricte des erreurs et réduction des risques mémoire.
- 🔍 **TUI & expérience terminal** : interface interactive avec recherche fuzzy, filtres par projet, branche Git, dossier et statut d’exécution.
- 🔒 **Confidentialité local-first** : données stockées localement, filtrage des commandes sensibles et absence de composant serveur.
- 🛡️ **Security by Design** : threat model, invariants de sécurité, protections contre les suppressions accidentelles, sauvegardes et restauration contrôlée.
- ⚙️ **Supply Chain Security** : dépendances auditées avec `cargo-audit`, `cargo-deny`, `cargo-machete`, checksums SHA-256, SBOM et signatures Sigstore/cosign.
- 🚀 **CI/CD DevSecOps** : workflows GitHub Actions avec `fmt`, `clippy`, tests, audit sécurité, détection de secrets, scripts shell vérifiés et releases reproductibles.

🔗 Repository  
https://github.com/Vesperis-group/mnemo

---

## 🛡️ Luphos

Plateforme de cybersécurité en développement, pensée pour centraliser des usages liés à la supervision, l’audit, l’automatisation et le durcissement d’environnements techniques.

Objectifs du projet :

- conception d’une plateforme cyber modulaire
- sécurité by design
- gestion des accès et des rôles
- journalisation et traçabilité
- architecture backend / frontend moderne
- automatisation et intégration de contrôles sécurité
- logique produit orientée environnements on-premise

Ce projet me permet d’approfondir des sujets proches du **DevSecOps**, de la **Cloud Security** et de l’**outillage sécurité interne**.

🌍 Site  
https://luphos.fr

---

## 🎣 GophishFR

Version francophone et adaptée de **GophishFR**, orientée simulation de phishing, sensibilisation et déploiement simplifié.

Objectifs :

- campagnes de sensibilisation au phishing
- adaptation à l’écosystème francophone
- déploiement simplifié sur environnements Linux
- packaging et automatisation
- sécurisation SMTP et intégration Microsoft 365
- documentation opérationnelle

🔗 Repository  
https://github.com/PassAndSecure/GophishFR

🌍 Site  
https://getgophishfr.com

---

## 🔐 Pass And Secure

Plateforme dédiée aux **tutoriels en cybersécurité, infrastructure et DevSecOps**.

Contenu :

- tutoriels techniques
- labs pratiques
- sécurité offensive et défensive
- infrastructure Linux / Windows
- automatisation
- bonnes pratiques opérationnelles

Ce projet me permet de combiner développement web, pédagogie, documentation technique et partage de connaissances autour de la cybersécurité.

🌍 Site  
https://passandsecure.fr

📦 GitHub  
https://github.com/PassAndSecure

---

## 🔑 KreatPass

Générateur de mots de passe **100% local** et respectueux de la vie privée.

Caractéristiques :

- génération locale
- aucune communication serveur
- mots de passe robustes
- logique simple, claire et orientée confidentialité

🔗 Repository  
https://github.com/Kirua6/KreatPass

---

# 📌 Ce que je construis

J’oriente mes projets autour de quelques principes simples :

- construire des outils utiles, pas seulement des démonstrations
- automatiser ce qui peut l’être
- intégrer la sécurité dès la conception
- documenter proprement les choix techniques
- privilégier les architectures maintenables
- apprendre en construisant des projets réels

---

# 📊 Métriques GitHub

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Kirua6&theme=tokyonight" height="170"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kirua6&theme=tokyo-night"/>
</p>

---

# 📫 Me contacter

- 🌍 Site CV : https://kvrcybertechno.fr
- 🔐 Pass And Secure : https://passandsecure.fr
- 🎣 GophishFR : https://getgophishfr.com
- 🧑‍💻 GitHub : https://github.com/Kirua6

---

<p align="center">
  <b>Cybersécurité pratique • Automatisation • DevSecOps • Open Source</b>
</p>
