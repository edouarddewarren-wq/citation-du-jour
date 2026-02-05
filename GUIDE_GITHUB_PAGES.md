# 🚀 Guide de Déploiement GitHub Pages - Citation du Jour

## Étape 1 : Créer un compte GitHub (si vous n'en avez pas)
1. Allez sur https://github.com
2. Cliquez sur "Sign up"
3. Suivez les instructions pour créer votre compte

## Étape 2 : Créer un nouveau dépôt
1. Une fois connecté, cliquez sur le bouton **"+" en haut à droite** → "New repository"
2. Remplissez les informations :
   - **Repository name** : `citation-du-jour` (ou un autre nom sans espaces)
   - **Description** : "Citation quotidienne inspirante pour TREVELIO"
   - **Public** (cochez cette option)
   - NE PAS initialiser avec README (décochez tout)
3. Cliquez sur **"Create repository"**

## Étape 3 : Obtenir l'URL de votre dépôt
Après création, GitHub vous affiche une page avec des commandes.
Copiez l'URL qui ressemble à : `https://github.com/votre-username/citation-du-jour.git`

## Étape 4 : Pusher vos fichiers

### Option A : Via l'interface GitHub (plus simple)
1. Sur la page de votre nouveau dépôt, cliquez sur **"uploading an existing file"**
2. Glissez-déposez ces 2 fichiers :
   - `citation_du_jour.html`
   - `README.md`
3. Ajoutez un message de commit : "Initial commit"
4. Cliquez sur **"Commit changes"**

### Option B : Via la ligne de commande (si vous êtes à l'aise)
Dans votre terminal, exécutez ces commandes :

```bash
cd /chemin/vers/vos/fichiers
git remote add origin https://github.com/VOTRE-USERNAME/citation-du-jour.git
git branch -M main
git push -u origin main
```

## Étape 5 : Activer GitHub Pages
1. Sur votre dépôt GitHub, allez dans **"Settings"** (onglet en haut)
2. Dans le menu de gauche, cliquez sur **"Pages"**
3. Sous "Branch", sélectionnez **"main"** (ou "master") et **/root**
4. Cliquez sur **"Save"**
5. Attendez 2-3 minutes

## Étape 6 : Récupérer votre URL publique
GitHub affichera un message vert avec votre URL :
```
Your site is live at https://VOTRE-USERNAME.github.io/citation-du-jour/
```

## 🎯 URL finale de votre citation
```
https://VOTRE-USERNAME.github.io/citation-du-jour/citation_du_jour.html
```

## 📌 Intégration dans une page web

Utilisez ce code iframe :

```html
<iframe src="https://VOTRE-USERNAME.github.io/citation-du-jour/citation_du_jour.html" 
        width="100%" 
        height="44" 
        frameborder="0" 
        scrolling="no"
        style="border: none;">
</iframe>
```

## 🔄 Mettre à jour le contenu

Pour modifier les citations ou le design :
1. Modifiez le fichier `citation_du_jour.html` localement
2. Sur GitHub, allez sur le fichier → cliquez sur l'icône crayon (Edit)
3. Faites vos modifications
4. Cliquez sur "Commit changes"
5. La mise à jour est automatique en 1-2 minutes

## ✅ Vérification

Une fois déployé, testez votre URL dans un navigateur.
Vous devriez voir la bannière avec la citation qui défile !

---

**Besoin d'aide ?**
Contact : edewarren@trevelio.fr
