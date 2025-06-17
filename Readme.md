# Text Summarization App

Application de résumé de texte utilisant un modèle Hugging Face avec interface Gradio.

## Installation

```bash
pip install transformers torch gradio python-dotenv pillow ipython
```

## Configuration

Créer un fichier `.env` :
```
HF_API_KEY=votre_clé_hugging_face
PORT1=7860
```

## Utilisation

Ouvrir et exécuter le notebook app.ipynb dans Jupyter

L'interface sera accessible sur `http://localhost:46313`

## Fonctionnalités

- Résumé automatique de texte avec le modèle `prithivMLmods/t5-Flan-Prompt-Enhance`
- Interface web simple avec Gradio
- Partage public optionnel