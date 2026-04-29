# SAÉ 4.DWeb-DI.01  – Développement d’un Réseau Social (BUT MMI – 2026)

## Présentation
Cette SAÉ s’inscrit dans le cadre du **BUT MMI (Métiers du Multimédia et de l’Internet)**.  
Elle a pour objectif de mobiliser les compétences en **développement web avancé**, **architecture logicielle**, **design d’interfaces** et **gestion de projet** à travers la création d’une application complète inspirée des réseaux sociaux modernes.

Ce projet est **individuel** et s’étend sur **5 semaines**, dont 4 en mode mixte (ressources + SAÉ) et 1 semaine entièrement dédiée au développement.

---

## Objectif du projet
L’objectif principal est de **concevoir et développer un réseau social complet**, similaire à Twitter ou Instagram, permettant aux utilisateurs de publier du contenu, d’interagir entre eux et de naviguer dans une interface moderne et réactive.

Contrairement aux projets de première année, cette SAÉ impose l’utilisation de **frameworks professionnels**, afin de démontrer une maîtrise réelle des outils modernes du développement web.

### Enjeux techniques
- Architecture **full-stack** moderne  
- Développement d’une **API REST** robuste  
- Gestion d’une base de données relationnelle  
- Interface client dynamique en **React**  
- Déploiement via **Docker**  
- Hébergement en production sur un serveur LAMP  

---

## Technologies utilisées

### 🖥️ Front-end
- **React**  
- **React Router DOM**  
- **Tailwind CSS**  
- **TypeScript**  
- **Figma** (wireframes et conception UI)

### ⚙️ Back-end
- **Symfony**  
- **Doctrine ORM**  
- **API REST** (échanges JSON)  
- **EasyAdmin** (back-office)

### 🛠️ Environnement & Déploiement
- **Docker** (front, back, base MySQL)  
- **MySQL**  
- **Git / GitHub** (branches par itération)  
- **Hébergement LAMP** (PulseHeberg ou mmi.unilim.fr)

---

## Méthodologie

Le projet suit une approche **itérative** :  
Chaque itération correspond à une version fonctionnelle (même partielle) de l’application.  
Les itérations sont regroupées en **cycles**, qui doivent être validés avant de passer au suivant.

### Organisation du travail
- **4 semaines mixtes** : 8h de SAÉ par semaine (4h encadrées + 4h autonomie)  
- **1 semaine 100% SAÉ**  
- **Branches Git** : `iteration-1`, `iteration-2`, etc.  
- **Merge par cycle** : une branche unique par cycle finalisé  

---

## Fonctionnalités développées

### 🔵 Front-Office (Utilisateur)
- Création de compte et authentification  
- Publication de posts (texte, images selon itérations)  
- Fil d’actualité dynamique  
- Système de likes / interactions  
- Profil utilisateur  
- Navigation client-side via React Router  
- Composants réutilisables basés sur un Design System  

### 🟣 Back-Office (Administrateur)
- Gestion des utilisateurs  
- Modération des contenus  
- Dashboard d’activité  
- Interface générée avec EasyAdmin  

### 🟠 API REST
- Endpoints sécurisés  
- Authentification (JWT ou session)  
- Réponses JSON  
- Validation des données  

---

## Hébergement
Les versions de production sont déployées sur un **hébergement LAMP**, tandis que l’environnement de développement repose entièrement sur **Docker**, garantissant une configuration reproductible et isolée.

---

## Remarques
Ce projet constitue un **prototype pédagogique** visant à démontrer la capacité à développer une application web moderne, structurée et scalable.  
Il met en avant la maîtrise des frameworks professionnels, la conception d’API, la gestion d’interfaces complexes et l’organisation du code en cycles et itérations.
