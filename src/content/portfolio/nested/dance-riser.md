---
title: Dance Riser
publishDate: 2022-11-04 00:00:00
img: /assets/dance-riser.com.jpg
img_alt: Application web 
description: |
  Nous avons développé en équipe (2 dev Back et 2 dev Front) une application API Rest avec Symfony et React.
tags:
  - PHP/Symfony
  - API
  - React
---

Le projet Dance Riser est né avec la perte du carnet de notes d'un professeur de break dance. Il s'est rendu compte qu'avec un support digital cela ne serait pas arrivé. Un premier site web a été créé, mais celui-ci a été mal conçu, le rendant inutilisable et non évolutif.

Le but de ce projet est donc de pouvoir offrir aux écoles, et également aux groupes de danseurs, un support, pour regrouper leurs mouvements et leurs chorégraphies. La plateforme vise à être un lieu d'échange entre le professeur et ses élèves, mais également entre les membres d'un groupe de danse.

Pour éviter le problème du premier site, l'objectif est de fournir un code qui respectera les bonnes pratiques, qui sera clair, commenté, et qui pourra évoluer afin d'ajouter de nouvelles fonctionnalités.

#### Les spécifications techniques

Technologies utilisées

- Technos front: React 18.2.0 , Redux 4.2.0, Axios 1.1.3, Sass 7.0.3, 1, BrowserRouter
- Technos back: Php 7.2, Symfony 5.4, Twig, mySQL, adminer.

#### Github

[voir le code pour le Back](https://github.com/nicolastaf/back-dance-riser)

#### Outils utilisés

- Figma -> wireframe
- Gloomaps -> sitemap
- Mocodo -> conception du MCD
- Vertabelo -> MCD / MLD / dictionnaire de données

#### Navigateurs utilisés

Liste des navigateurs disponibles :

- Google Chrome
- Safari
- Mozilla Firefox

#### Cible

Les cibles sont :

- écoles de Hip-Hop
- élève
- professeur.
- adolescent (à partir de 11).
- parents d’élèves

#### Rôles

Nous avons définis les rôles :

- Product Owner : Aymeric, il se chargera de la relation avec le responsable de la salle hip hop pour avoir le détail des besoins.
- Scrum Master : Aurélien, il se chargera de l’organisation du check up quotidien et de la rédaction du carnet d’équipe.
- Lead Dev Front : Idris, il prendra les décisions liées au front
- Lead Dev Back : Nicolas, il prendra les décisions liées au back
- Git Master : Aymeric, il sera responsable de la gestion de github

#### End points

Un exemple de quelques routes Front, la liste complète est trop longue...

| Url                   | API à créer               | API method |
| --------------------- | ------------------------- | ---------- |
| /                     | /api/home                 | GET        |
| /user                 |                           |            |
| /user/settings        | /api/user/settings        | GET/PATCH  |
| /login                | /api/login                | POST       |
| /subscribe            | /api/subscribe            | POST       |
| /school-membership    |                           | POST       |
| /schools              | /api/schools              |            |
| /schools/{slugSchool} | /api/schools/{slugSchool} |            |
| /schools/add          | /api/schools/add          | POST       |
| /events               | /api/events               |            |
| /events/{slugEvent}   | /api/events/              |            |
| /contact              | /api/contact              | POST       |
| /moves                | /api/styles               | GET        |
| /moves/{slugStyle}    | /api/styles/category      | GET        |


### User Story

Voici un exemple

| En tant que           | Je veux                                                                   | Afin de (si besoin/nécessaire)                                                 |
| --------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| User stories Visiteur |                                                                           |                                                                                |
| visiteur              | Je veux pouvoir accéder à la Homepage du site                             | afin d'en apprendre plus sur le site                                           |
| visiteur              | Je veux pouvoir accéder à la page de connexion/ inscription               | afin de me connecter ou de m'inscrire                                          |
| visiteur              | Je veux pouvoir accéder à la liste des événements organisé par les écoles | afin de me renseigner sur le lieu et/ou la date de celui-ci                    |
| visiteur              | Je veux pouvoir accéder à un événement en particulier                     | afin de me renseigner sur son lieu et/ou sa date ou encore l'école de celui-ci |
| visiteur              | Je veux pouvoir accéder à la liste des écoles                             | afin de me renseigner sur les écoles disponibles sur le site                   |
| visiteur              | Je veux pouvoir accéder à la page d'une école                             | afin de me renseigner sur celle-ci                                             |
| visiteur              | Je veux pouvoir accéder à la page des sponsors                            | afin de voir qui soutient le site                                              |
| visiteur              | Je veux pouvoir accéder à la page de contact                              | afin de contacter les gérant du site                                           |
| visiteur              | Je veux pouvoir envoyer un mail via la page de contact                    | afin de visualiser les mouvements disponibles de base                          |
| visiteur              | Je veux acceder aux conditions générales d'utilisations                   | afin de voir les conditions générales d'utilisations du site internet          |
| visiteur              | Je veux acceder au plan du site                                           | afin de voir le plan du site                                                   |


Il reste les wireframes, le MCD, le MLD et le dictionnaire de données, ces ficheirs étant très nombreux je vai sm'arrêter là pour ce projet.