# 🤖 ChatGPT Discord Bot - Votre assistant IA sur Discord

[![Discord](https://img.shields.io/discord/869149763558342686?color=%237289DA&label=Join%20Discord&logo=discord&style=for-the-badge)](https://discord.gg/yTvzufG63a)
[![Version](https://img.shields.io/github/package-json/v/clement-skyway/Bot-ChatGPT?style=for-the-badge)](https://github.com/clement-skyway/Bot-ChatGPT/releases)
[![License: MIT](https://img.shields.io/github/license/clement-skyway/Bot-ChatGPT?style=for-the-badge)](LICENSE)

- ATTENTION : Ce robot n'est en aucun cas affilié avec OpenAI et ne fonctionne pas grâce au GPT4 officiel.
- WARNING: This robot is in no way affiliated with OpenAI, and does not work with the official GPT4.

---

## 🎯 Fonctionnalités

- **Assistant IA** : Posez vos questions, obtenez des réponses complexes et engagez des conversations en langage naturel avec le modèle ChatGPT.
- **Personnalisation** : Configurez des paramètres spécifiques à votre serveur pour un comportement sur mesure.
- **Modération d'IA** : Aide à la gestion des conversations et détection de comportements inappropriés.
- **Support Multilingue** : Capable de discuter dans différentes langues, y compris le français, l'anglais, l'espagnol, et plus encore.
- **Intégration simple** : Ajoutez le bot à votre serveur en quelques clics.

---

## 🚀 Comment démarrer

### Prérequis

Avant de démarrer, vous aurez besoin des éléments suivants :

- [Node.js](https://nodejs.org/) version 16 ou supérieure
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

---

### Installation

1. Clonez ce repository sur votre machine locale :
  ```
  git clone https://github.com/MaitreCapybaraoff/Capy-GPT-BOT.git
  ```

2. Accédez au répertoire du bot :
  ```
  cd Capy-GPT-BOT
  ```

3. Installez les dépendances nécessaires :
  ```
  npm install
  ```

4. Créez un fichier .env en vous basant sur le fichier .env.example et ajoutez-y votre clé d'API SkyWay ainsi que d'autres informations sensibles :
  ```
  cp .env.example .env
  ```

5. Insérer le token de votre bot Discord dans le fichier .env (assurez vous d'avoir activé l'intent Message)
  ```
  TOKEN=LE_TOKEN_DE_VOTRE_BOT
  ```

6. Mettre à jour le fichier .env avec votre clé d'API obtenue via SkyWay.
  ```
  API_KEY=VOTRE_CLE_API
  ```

7. Lancer le robot 

- Sous NodeJS
  ```
  node index.js
  ```

- Sous Yarn
  ```
  yarn run node index.js
  ```

### Configuration

Le robot est entièrement configurable via un fichier .env Exemple de configuration :
  ```
  TOKEN=LE_TOKEN_DE_VOTRE_BOT
  CHANNEL_ID=ID_DU_SALON
  API_KEY=VOTRE_CLE_API
  ```

  ---

## 🛠️ Contribution

Les contributions sont **les bienvenues** ! Suivez ces étapes pour contribuer au projet :

1. Forker le projet
2. Créer une branche spécifique pour votre fonctionnalité (`git checkout -b feature/ma-fonctionnalite`)
3. Committez vos changements (`git commit -am 'Ajout de ma fonctionnalité'`)
4. Poussez la branche (`git push origin feature/ma-fonctionnalite`)
5. Ouvrez une Pull Request
