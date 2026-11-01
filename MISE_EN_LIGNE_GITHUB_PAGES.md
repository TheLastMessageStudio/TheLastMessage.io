# Publier le site officiel avec GitHub Pages

Le site est dans ce dossier `docs/`. Il est indépendant de l’application Flutter : tu peux publier uniquement ce dossier sur GitHub, sans rendre le code source de l’application public.

## Depuis GitHub (sans installer de logiciel)

1. Ouvre https://github.com/yuuuuuuuuuuuuuuuuuuuki/The-Message-App
2. Dans l’onglet **Code**, clique sur **Add file** puis **Upload files**.
3. Sur ton ordinateur, ouvre le dossier `docs` fourni avec le projet. Glisse-dépose **le dossier `docs` entier** (ou ses deux éléments `index.html` et `assets/`) dans la zone d’envoi.
4. En bas, clique sur **Commit changes** et confirme.
5. Dans le dépôt, ouvre **Settings** puis **Pages**.
6. Dans **Build and deployment**, choisis **Deploy from a branch**.
7. Branche : **main** (ou la branche par défaut du dépôt). Dossier : **/docs**. Clique **Save**.
8. Attends quelques minutes. Le site devrait être accessible à l’adresse :
   https://yuuuuuuuuuuuuuuuuuuuki.github.io/The-Message-App/

## Contenu du site

- Page d’accueil en français, anglais et arabe.
- Bouton de téléchargement qui ouvre la dernière version GitHub :
  https://github.com/yuuuuuuuuuuuuuuuuuuuki/The-Message-App/releases/latest
- Bouton vers le dépôt GitHub.
- Petit tutoriel Android pour télécharger et installer `app-release.apk`.

## Important

Ne téléverse pas le dossier complet du projet Flutter si tu souhaites garder le code source privé. Pour publier le site, téléverse seulement `docs/` (et conserve le README à la racine si tu le souhaites). Les APK restent dans **Releases**, pas dans le dossier `docs`.
