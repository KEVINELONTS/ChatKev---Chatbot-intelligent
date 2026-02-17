ChatKev---Chatbot-intelligent
ChatKev - Chatbot intelligent propulsé par plusieurs modèles d'IA (Llama 3, Gemini, GPT-3.5, Mistral) via OpenRouter API. Développé en HTML, CSS et JavaScript vanilla.

 ChatKev - Assistant Intelligent

ChatKev est un chatbot pédagogique intelligent développé en HTML, CSS et JavaScript . 
Il exploite plusieurs modèles d'intelligence artificielle via l'API OpenRouter pour fournir 
des réponses précises et contextualisées.

Fonctionnalités

-  Interface de chat moderne et responsive
-  Design élégant avec effets glass morphism et gradients animés
-  Intégration de plusieurs modèles d'IA via OpenRouter
-  Indicateur de frappe animé
-  Compatible mobile et desktop
  Gestion sécurisée des erreurs API

Technologies utilisées

- **HTML5** - Structure de l'interface
- **CSS3 / TailwindCSS** - Design et animations
- **JavaScript (Vanilla)** - Logique et appels API
- **OpenRouter API** - Accès aux modèles d'IA
- **Font Awesome** - Icônes

Modèles d'IA disponibles

| Modèle | Créateur | Usage |
|--------|----------|-------|
| `meta-llama/llama-3-8b-instruct` | Meta | Conversations générales |
| `google/gemini-2.0-flash-001` | Google | Réponses rapides et précises |
| `google/gemini-2.0-flash-lite-001` | Google | Tâches légères |
| `mistralai/devstral-2512` | Mistral AI 🇫🇷 | Code et programmation |
| `openai/gpt-3.5-turbo` | OpenAI | Conversations avancées |

 Installation

1. Clonez le repository :
git clone https://github.com/votre-username/chatKev.git

2. Ouvrez le fichier index.html dans votre navigateur

3. Ajoutez votre clé API OpenRouter dans le fichier :
const API_KEY = "votre-clé-api-ici";

4. Choisissez votre modèle d'IA :
const MODEL = MODEL_GEMINI; // ou MODEL_LLAMA, MODEL_GPT...

Configuration OpenRouter

1. Créez un compte sur [openrouter.ai](https://openrouter.ai)
2. Générez une clé API
3. Collez-la dans le code

 Important: Ne partagez jamais votre clé API publiquement !

Structure du projet

chatKev/
├── index.html        # Structure principale
├── README.md         # Documentation
└── assets/           # Ressources (images, icônes...)

 Cas d'usage

- Assistant pédagogique pour étudiants
- Chatbot de support client
- Assistant interne d'entreprise
- Prototype de chatbot personnalisé
Aperçu

![ChatKev Preview](screenshot.png)

##  Améliorations futures

- [ ] Sécurisation de la clé API via backend
- [ ] Sauvegarde de l'historique des conversations
- [ ] Support du markdown dans les réponses
- [ ] Mode sombre / clair
- [ ] Choix du modèle directement dans l'interface
- [ ] Export des conversations en PDF

# Auteur

Développé par **Kev**

 Licence

MIT License - Libre d'utilisation et de modification
```

---
 📌 **Version ultra courte (bio GitHub) :**
```
🤖 ChatKev | Chatbot IA multi-modèles (Llama 3, Gemini, GPT) | HTML • CSS • JavaScript • OpenRouter API
