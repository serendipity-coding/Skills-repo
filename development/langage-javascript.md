# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

> 👌 Validation par le formateur

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage  ✔️
- les normes `ecmascript`  ✔️
- l'utilisation de l'`asynchrone` ✔️
- les spécifités du mot-clef `this`  ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

```javascript
// Fetch random user and add money than populate UI
async function getRandomUser() {
    const res = await fetch('https://randomuser.me/api');
    const data = await res.json();
    const user = data.results[0];

    const newUser = {
        name: `${user.name.first} ${user.name.last}`,
        money: Math.floor(Math.random() * 1000000)
    };
    addData(newUser);
}
```

### Utilisation dans un projet ✔️

[https://github.com/serendipity-coding/P05-e-commerce-website](...)

Description :
J'ai utilisé JS pour réaliser un site e-commerce avec les fonctionnalités suivantes:
-Affichages des produits
-Affichage un seul produits en détails
-Ajouter un produits au panier
-Modifier quantité et supprimer produits du panier
-Valider la commande par un formulaire

### J'ai utilisé ce langage en production ❌ 

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel  ✔️

Description : 

Realisation d'une application de JobDating

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ 
-Gestion de data
-aintenir un code propre et reutilisable

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

