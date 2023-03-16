---
isIndex: false
draft: false
date: 2023-01-02T19:34:08.410Z
title: T design
image:
  src: /images/uploads/tdesign-logo.svg
hero:
  surtitle: Étude de cas
  title: T design, Migration d’un site PHP (non open-source) vers Architectify
  image:
    src: /images/uploads/tdesign-logo.svg
blocks:
  - type: paragraph
    title: Quelques mots sur le cabinet
    text: Architecture générale et d'intérieur, réhabilitation immobilière,
      construction HQE / BBC, basse énergie, design, mobilier.
    grid: medium
    align: center
    offset: center
  - align: start
    grid: small
    text: La précédente version du site a été créé grâce à un système de gestion de
      contenu propriétaire. Écrit en PHP, il repose sur une base de données
      MySQL. Cela implique un hébergement sur serveur Apache et une maintenance
      du système.
    background: false
    offset: start
    title: État des lieux
    type: editorial
    image:
      src: /images/uploads/logo-php-apache-mysql.jpeg
    direction: rtl
  - type: quote
    text: « Il nous fallait un site évolutif et maintenable dans le temps »
    author:
      title: Frédéric Thet
      text: T design architecture
  - type: datas
    title: Analyse de l’ancien site du cabinet
    text: Grâce à Google Lighthouse qui est un outil open source permettant de
      mesurer la qualité des pages Web. Voici, ci-dessous, le test de la page
      d’accueil sur mobile.
    column: 4
    show_color: true
    show_gauge: true
    items:
      - title: Performance
        value: 71
        suffix: "%"
        limit: 100
      - title: Accessibilité
        value: 96
        suffix: "%"
        limit: 100
      - title: Meilleures pratiques
        value: 83
        suffix: "%"
        limit: 100
      - title: Référencement (SE0)
        value: 79
        suffix: "%"
        limit: 100
  - type: informations
    column: 3
    background: false
    title: Pourquoi améliorer ces critères ?
    items:
      - icon: people
        title: Pour vos utilisateurs
        text: "Un site plus léger, c'est une meilleure expérience : les pages se
          chargent rapidement, même sur mobile et même si le réseau n'est pas
          très bon."
      - icon: graph-up-arrow
        title: Pour votre activité
        text: Un site web plus rapide, c'est une meilleure performance business. Cela a
          aussi de nombreux autres impacts positifs.
      - title: Pour votre empreinte carbone
        icon: globe-europe-africa
        text: En ayant un site web non énergivore vous réduirez considérablement votre
          impact environnemental.
  - type: images
    title: Comparaison des espaces d’administration
    text: D’un côté un admin compliqué et parasité par des fonctionnalités inutiles
      au cabinet. De l’autre coté un admin dédié et simplifié pour le cabinet.
    background: false
    images:
      - src: ""
        legend: Admin de l’ancien site
        half: true
      - src: /images/uploads/tdesign-screenshot-admin.png
        legend: Admin Architectify dédié au cabinet
        half: true
  - type: quote
    text: « Architectify nous a permis d’avoir un site web bas carbon et
      accessible. »
    author:
      title: Frédéric Thet
      text: T design architecture
  - type: datas
    title: Analyse du nouveau site du cabinet
    text: Grâce à Architectify, tous les voyants sont au vert !
    column: 4
    show_color: true
    show_gauge: true
    items:
      - title: Performance
        limit: 100
        suffix: "%"
        value: 98
      - title: Accessibilité
        value: 100
        suffix: "%"
        limit: 100
      - title: Meilleures pratiques
        value: 100
        suffix: "%"
        limit: 100
      - title: Référencement (SE0)
        value: 100
        limit: 100
        suffix: "%"
  - type: cta
    cta:
      text: Découvrez le site web du cabinet T design
      url: https://tdesignarchitecture.com/
      blank: true
---
