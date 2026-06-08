# IA Codeur 🤖

Un chatbot IA spécialisé en code, que tu peux entraîner avec ta propre connaissance.

## Installation (2 minutes)

1. **Télécharge** ce dossier sur ton ordinateur
2. **Ouvre** `chatbot.html` dans ton navigateur
3. **Entre ta clé API Groq** en haut de la page (console.groq.com)
4. **C'est prêt !**

## Comment "entraîner" ton IA

Clique sur **📚 Connaissance** à droite pour ouvrir le panneau.

Tu peux ajouter autant de "fiches de connaissance" que tu veux :

- **Tes fonctions** : colle ton code que tu réutilises souvent
- **Tes conventions** : comment tu veux que l'IA réponde
- **De la doc** : colle la documentation d'un framework
- **Des exemples** : montre à l'IA exactement comment répondre

Chaque fiche peut être activée/désactivée avec le toggle.
Plus tu ajoutes de contenu, mieux l'IA comprend ton style !

## Intégrer sur ton site HTML

Ajoute ce bouton sur ton site :

```html
<a href="chatbot.html" target="_blank">
  <button>💬 Parler à l'IA</button>
</a>
```

Ou intègre directement dans une iframe :

```html
<iframe src="chatbot.html" width="100%" height="600px" frameborder="0"></iframe>
```

## Structure des fichiers

```
ia-codeur/
├── chatbot.html          ← le chatbot complet
├── README.md             ← ce fichier
└── connaissance/
    ├── style.md          ← exemple de conventions
    └── exemples.md       ← exemple de code
```

## Modèle IA utilisé

- **Groq** avec **Llama 4** (gratuit, ultra rapide)
- Clé API gratuite sur : console.groq.com

## Données

Tout est sauvegardé dans ton navigateur (localStorage).
Rien n'est envoyé ailleurs que l'API Groq.
