# AfricaTube — prototype fonctionnel

Site web responsive en français, avec identité visuelle blanche et verte et le logo couronne fourni.

## Lancer sur son ordinateur
1. Décompresse `AfricaTube.zip`.
2. Ouvre le dossier `AfricaTube`.
3. Double-clique sur `index.html` pour ouvrir le site dans ton navigateur.
4. Pour un meilleur résultat, lance-le avec un petit serveur local (par exemple l'extension Live Server de Visual Studio Code).

## Fonctions incluses
- Page d'accueil responsive et navigation par catégories
- Recherche dans les vidéos de démonstration
- Lecteur vidéo intégré via des vidéos de démonstration hébergées par YouTube
- Likes et commentaires de démonstration dans la session
- Formulaire de publication permettant de prévisualiser localement une vidéo
- Connexion de démonstration, sans compte ni mot de passe
- Fenêtre « À propos »

## Important : ce qui n'est pas encore un vrai service en ligne
Ce prototype est un **front-end**. Les vidéos ajoutées sont locales à ton navigateur/appareil et ne sont pas envoyées sur Internet. Les comptes, commentaires et likes ne sont pas enregistrés dans une base de données. Il n'y a pas encore de système de modération, de signalement, de droits d'auteur, ni d'administration sécurisée.

Pour lancer une plateforme publique, il faudra ajouter :
- une base de données et une authentification réelle ;
- un stockage et une diffusion vidéo (coûts et limites à vérifier) ;
- des règles de modération, de confidentialité et de retrait des contenus ;
- des protections contre les abus et un système de sauvegarde.

## Publier gratuitement avec GitHub Pages
1. Crée un compte sur GitHub si tu n'en as pas.
2. Crée un dépôt public nommé `africatube`.
3. Envoie **le contenu du dossier** `AfricaTube` dans le dépôt : `index.html`, `styles.css`, `app.js`, `README.md` et le dossier `assets`.
4. Dans le dépôt, ouvre **Settings → Pages**.
5. Sous **Build and deployment**, choisis **Deploy from a branch**, sélectionne `main` et `/ (root)`, puis clique sur **Save**.
6. Attends la publication. GitHub affichera l'adresse de ton site dans la section Pages, généralement `https://TON-PSEUDO.github.io/africatube/`.

Les intitulés peuvent varier légèrement selon l'interface de GitHub. Avec GitHub Pages, le site statique est gratuit selon les conditions de GitHub, mais cela ne fournit pas de stockage vidéo partagé ni de backend.

## Personnalisation
- Logo : remplace `assets/logo-africatube.jpg` par ton fichier logo (garde le même nom).
- Couleur principale : change `--green` dans `styles.css`.
- Vidéos de démonstration : modifie la liste `videos` dans `app.js`.
