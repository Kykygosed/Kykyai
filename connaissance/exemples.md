# Mes exemples de code

## Exemple : fonction utilitaire JS
```javascript
// Formater une date en français
const formaterDate = (date) => {
    return new Intl.DateTimeFormat('fr-FR').format(new Date(date))
}
```

## Exemple : fetch avec gestion d'erreur
```javascript
const fetchDonnees = async (url) => {
    try {
        const reponse = await fetch(url)
        if (!reponse.ok) throw new Error('Erreur réseau')
        return await reponse.json()
    } catch (erreur) {
        console.error('Problème :', erreur)
        return null
    }
}
```

## Exemple : manipulation du DOM
```javascript
// Ajouter un élément proprement
const ajouterElement = (parent, texte) => {
    const el = document.createElement('div')
    el.textContent = texte
    el.classList.add('mon-element')
    document.querySelector(parent).appendChild(el)
}
```
