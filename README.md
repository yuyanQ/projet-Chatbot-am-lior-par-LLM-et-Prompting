## Solution d'Amélioration des Réponses du Chatbot

### Objectif

Optimiser la précision et la pertinence des réponses du chatbot technique en utilisant une base de données SQLite.

### Méthodologie

- Analyse de Données : Gestion et analyse des titres et contenus via SQLite.
- Prétraitement : Contextualisation et vectorisation des titres avec ```SentenceTransformer```.
- Récupération de Contenu : Matching via similarité cosinus pour trouver les titres les plus proches avec URL.
- Génération de Réponses : Utilisation de GPT-3.5-turbo pour reformuler les réponses.
