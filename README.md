# Transcritex

Transcritex est une application web simple et robuste qui utilise OpenAI Whisper pour transcrire des fichiers audio en texte. Développée en React pour le frontend et Express pour le backend, cette application permet de convertir facilement la parole en texte.

## Fonctionnalités

- Téléchargement de fichiers audio
- Transcription automatique de l'audio en texte
- Affichage du texte transcrit

## Prérequis

- Node.js
- npm (ou yarn)
- Clé API OpenAI

## Installation

1. Clonez le dépôt :

```bash
git clone https://github.com/votre_nom_utilisateur/Transcritex.git
cd Transcritex
```

2. Installez les dépendances pour le frontend et le backend :

```bash
cd audio-transcription-app
npm install
cd ../backend
npm install
```

3. Configurez votre clé API OpenAI :

- Créez un fichier .env dans le dossier backend et ajoutez votre clé API :

  ```makefile
  OPENAI_API_KEY=your_openai_api_key
  ```

## Utilisation

1. Démarrez le backend :

```bash
cd backend
node index.js
```

2. Démarrez le frontend :

```bash
cd ../audio-transcription-app
npm start
```

3. Ouvrez votre navigateur et accédez à http://localhost:3000.
