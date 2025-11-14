# Site de l'Amicale d'Arbère

Ce dépôt contient le site vitrine statique de l’Amicale d’Arbère (école d’Arbère, Divonne-les-Bains), déployé via GitHub Pages.

URL du site : https://wakingga.github.io/amicale-arbere/

## Objectif du site

- Présenter **les prochains événements** organisés par l’Amicale (page d’accueil).
- Expliquer **qui est l’association**, sa mission et son mode de financement (page À propos).
- Faciliter le **contact** avec l’Amicale (email).

Le contenu est pour l’instant un **draft** destiné à être présenté au bureau de l’association. Les chiffres et certaines infos sont volontairement approximatifs et pourront être ajustés après validation.

## Structure des pages

- `index.html`  
  Page d’accueil centrée sur les **prochains événements** :
  - Hero avec logo et tagline
  - Section "Prochains événements" avec cartes détaillées (date, lieu, horaire, type)
  - CTA vers la page À propos
  - Section Contact (email, localisation)

- `about.html`  
  Page **À propos de l’Amicale** :
  - Présentation générale de l’association
  - Mission (financer, rassembler, animer)
  - Description des principaux événements de financement (Illuminations, fondues, fête de l’école)
  - Bloc "Impact" avec quelques chiffres

- `style.css`  
  Styles globaux du site :
  - Palette de couleurs correspondant au logo
  - Layout responsive (desktop + mobile)
  - Composants : header/nav, hero, cartes événements, timeline, stats, CTA, etc.

- `logo.png`  
  Logo de l’Amicale sur fond blanc, utilisé dans le header et le hero.

## Développement local

1. Cloner le repo :

   ```bash
   git clone https://github.com/wakingga/amicale-arbere.git
   cd amicale-arbere