# MiraLightning WebUI

## Introduction

**MiraLightning** est un projet personnel d'**IoT** se basant sur l'environnement *Philips Hue*.
Le but de ce projet est de construire un éco-système d'éclairage polyvalent, tout en apportant des fontionnalités non implémentées par les applications *Philips Hue*.

Ce projet regroupera, à terme, plusieurs technologies, dont le développement :
- d'une interface web et d'une API
- de plusieurs systèmes embarqués (Arduino),
- d'une application Android.

## Repo - Interface web

Ce repo GitHub contient l'interface web ainsi que l'API reliant chaque Arduino.

### Installation

Cloner le repo avec:
```
git clone https://github.com/gregoirebiendine/miralightning-webui.git
```

Executer ces commandes pour installer les dépendances et lancer le serveur:
```
cd miralightning-webui
npm -i
npm run start
```

Aller à l'adresse http://localhost:3000

## Technologie(s) utilisée(s)

- ReactJS
- TailwindCSS