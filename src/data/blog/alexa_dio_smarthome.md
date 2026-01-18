---
title: "Créer une skill Alexa Smart Home pour DIO Home"
description: "Retour d’expérience sur une intégration Alexa Smart Home v3 avec une box DIO"
pubDate: 2026-01-15T00:00:00.000Z
tags:
  - alexa
  - iot
  - aws
  - dio
  - smarthome
---

## Introduction

Dans cet article, je présente comment j’ai développé une **Alexa Smart Home Skill v3**
pour piloter une box **DIO Home**, en abordant :

- l’Account Linking
- OAuth minimal
- Lambda Smart Home
- Discovery & PowerController

## Architecture

```text
Alexa → Lambda Smart Home → Box DIO
