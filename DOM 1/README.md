# Shopping Cart - DOM Events

Un panier d'achat entièrement fonctionnel avec gestion des événements DOM en JavaScript vanille.

## 🎯 Fonctionnalités

✅ Ajuster la quantité de chaque article avec les boutons "+" et "-"  
✅ Supprimer des articles du panier  
✅ Aimer des articles avec un bouton cœur cliquable (change de couleur)  
✅ Voir le prix total ajusté en temps réel  
✅ Animations fluides lors de la suppression d'articles  
✅ Compteur d'articles dans le header  

## 📁 Structure du Projet

```
DOM 1/
├── Index.html      # Fichier principal (HTML, CSS, JS)
├── .gitignore      # Fichiers à ignorer par Git
└── README.md       # Ce fichier
```

## 🚀 Démarrage Rapide

1. Clonez le dépôt :
```bash
git clone https://github.com/DJCKRUZ/DOM-1.git
cd DOM-1
```

2. Ouvrez le fichier dans votre navigateur :
```bash
# Avec VS Code Live Server
code Index.html
```

Ou simplement ouvrez `Index.html` dans votre navigateur préféré.

## 💻 Technologie

- **HTML5** - Structure sémantique
- **CSS3** - Styles modernes avec variables CSS et animations
- **JavaScript (Vanilla)** - Événements DOM avec `addEventListener()`

## 🎨 Caractéristiques de Design

- Interface responsive
- Animations fluides
- Variables CSS pour une personnalisation facile
- Icons SVG intégrées
- Format de devises localisé (EUR)

## 📝 Gestion des Événements DOM

Le projet utilise les meilleures pratiques :
- ✅ `addEventListener()` pour l'attachement des événements
- ✅ Attributs `data-*` pour le stockage des données
- ✅ Sélection d'éléments avec `querySelector()`
- ✅ Manipulation du DOM avec `createElement()` et `innerHTML`

## 🔄 Flux de Rendus

Toute action (ajout, suppression, modification) déclenche la fonction `renderCart()` qui :
1. Recalcule le total et le compteur
2. Re-crée tous les éléments du DOM
3. Ré-attache tous les event listeners
4. Met à jour l'affichage

## 📦 Données Initiales

Le panier démarre avec 3 articles :
1. **Casque Audio Sans Fil** - 249.99 €
2. **Montre Connectée Sport** - 129.50 €
3. **Baskets Urbaines** - 89.00 € (quantité: 2)

## 📄 Licence

Ce projet est open source et libre d'utilisation.

## 👤 Auteur

**DJCKRUZ** - GitHub: [@DJCKRUZ](https://github.com/DJCKRUZ)

---

**Lien du dépôt :** https://github.com/DJCKRUZ/DOM-1
