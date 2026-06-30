# 🌊 Astérina Meaux — Club de Plongée Sous-Marine

> Refonte moderne, fluide et responsive du site internet officiel d'Astérina Meaux (Club de plongée sous-marine à Meaux, Seine-et-Marne).

![Version](https://img.shields.io/badge/Version-2026-0066b2?style=flat-square)
![Framework](https://img.shields.io/badge/UI_Framework-Tailwind_CSS_v3-2bc0d1?style=flat-square&logo=tailwind-css)
![Licence](https://img.shields.io/badge/Design_Origine-LV_2022-f07151?style=flat-square)

---

## 📋 Présentation du projet

Ce projet consiste en une modernisation complète de l'architecture front-end du site de l'association de plongée **Astérina**. L'objectif principal était de remplacer l'ancienne structure rigide en tableaux HTML et feuilles de styles legacy par une interface utilisateur épurée, sémantique et parfaitement adaptée aux smartphones et tablettes, tout en conservant l'intégralité du contenu historique (médias, trombinoscopes, documents).

### ✨ Fonctionnalités clés
*   **Trombinoscopes dynamiques :** Section du personnel et des moniteurs réorganisée sous forme de grilles de cartes interactives avec catégorisation par niveau de diplôme (badges E1 à E4).
*   **Médiathèque des sorties :** Valorisation des archives vidéo (.mp4) et des albums photo des voyages mythiques (Corse, Mexique, Afrique du Sud).
*   **Espace Téléchargements :** Centralisation ergonomique des fiches d'inscription (Adultes/Enfants), règlements intérieurs, statuts de l'association et cours théoriques.
*   **Design Fluide :** Utilisation de l'effet *backdrop-blur* (flou d'arrière-plan sur le menu collant), de transitions douces au survol et d'une palette de couleurs inspirée de l'univers océanique.

---

## 🛠️ Technologies utilisées

*   **HTML5** — Structure sémantique et accessibilité.
*   **Tailwind CSS** — Framework utilitaire pour un design *mobile-first* ultra-rapide sans feuilles de style volumineuses.
*   **FontAwesome v6** — Banque d'icônes vectorielles pour enrichir l'interface graphique.
*   **Google Fonts** — Typographie *Plus Jakarta Sans* & *Inter* pour une lisibilité maximale.

---

## 📁 Structure du projet

Voici l'organisation des principaux fichiers et dossiers de ce dépôt :

```text
├── index.html                           # Page d'accueil (Club)
├── La_Piscine.html                      # Informations sur l'accès aux bassins
├── Le_Staff.html                        # Hub d'accès au bureau et aux moniteurs
├── Le_Bureau.html                       # Trombinoscope des membres du bureau élu
├── Les_moniteurs.html                   # Liste de l'équipe pédagogique (E1 à E4)
├── Les_Sorties.html                     # Calendrier des voyages et archives multimédias
├── Les_telechargements.html             # Accès aux formulaires PDF et cours théoriques
├── Les_Formations.html                  # Cursus de formation dispensés
│
├── images/                              # Dossier des ressources graphiques
│   ├── Nouveau_logo_complet.jpg         # Logo officiel d'Astérina
│   ├── TROMBI/                          # Photos d'identité de l'équipe
│   ├── Photo_plongee/                   # Galerie photos des sorties clubs
│   ├── video/                           # Fichiers vidéos (.mp4) des 40 ans et voyages
│   └── Documents_PDF/                   # Statuts, règlements et logos fédéraux
