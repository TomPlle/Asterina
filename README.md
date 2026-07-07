# 🌊 Astérina Meaux — Club de Plongée Sous-Marine

> Refonte moderne, fluide et responsive du site internet officiel d'Astérina Meaux (Club de plongée sous-marine à Meaux, Seine-et-Marne).

![Version](https://img.shields.io/badge/Version-2026-0066b2?style=flat-square)
![Framework](https://img.shields.io/badge/UI_Framework-Tailwind_CSS_v3-2bc0d1?style=flat-square&logo=tailwind-css)
![Licence](https://img.shields.io/badge/Design_Origine-LV_2022-f07151?style=flat-square)

---

## 📋 Présentation du projet

Ce projet consiste en une modernisation complète de l'architecture front-end du site de l'association de plongée **Astérina**. L'objectif était de transformer une structure héritée en une interface utilisateur moderne, sémantique et optimisée pour tous les appareils, tout en améliorant l'expérience de navigation pour les membres.

### ✨ Fonctionnalités clés
* **Navigation Intuitive :** Menu collant avec effet *backdrop-blur* pour une expérience de lecture immersive.
* **Espace Téléchargements Interactif :** Système d'accordéons dynamiques permettant d'accéder aux dossiers d'inscription, fiches médicales, et archives (Bureau/Moniteurs) de manière organisée.
* **Cursus de Formation Structuré :** Page dédiée aux formations, utilisant des cartes interactives détaillant les prérequis pour chaque niveau (Baptême au Niveau III), avec une section spéciale pour les encadrants.
* **Trombinoscopes & Médias :** Grilles de cartes pour le staff et galerie de photos des sorties, valorisant les archives historiques du club.

---

## 🛠️ Technologies utilisées

* **HTML5** — Structure sémantique et accessibilité.
* **Tailwind CSS** — Framework utilitaire pour un design *mobile-first* performant.
* **JavaScript (Vanilla)** — Gestion légère de l'interactivité (accordéons).
* **FontAwesome v6** — Icônes vectorielles pour une interface claire.
* **Google Fonts** — Typographie *Plus Jakarta Sans* & *Inter*.

---

## 📁 Structure du projet

Voici l'organisation des principaux fichiers et dossiers de ce dépôt :

```text
├── index.html                  # Page d'accueil (Club)
├── La_Piscine.html             # Informations sur l'accès aux bassins
├── Le_Staff.html               # Hub d'accès au bureau et aux moniteurs
├── Le_Bureau.html              # Trombinoscope des membres du bureau élu
├── Les_moniteurs.html          # Liste de l'équipe pédagogique (E1 à E4)
├── Les_Sorties.html            # Calendrier des voyages et archives multimédias
├── Les_telechargements.html    # Accès aux formulaires, cours théoriques et CR
├── Les_Formations.html         # Cursus de formation (Niveaux 1 à III)
│
├── images/                     # Dossier des ressources graphiques
│   ├── Logos/                  # Dossier de l'ensemble des logos utilisés
│   ├── index/                  # Dossier des images décoratives de la page index.html
│   ├── TROMBI/                 # Photos d'identité de l'équipe
│   ├── Photo_plongee/          # Galerie photos des sorties clubs
│   ├── video/                  # Fichiers vidéos (.mp4)
│   └── Documents_PDF/          # Statuts, règlements et logos fédéraux
