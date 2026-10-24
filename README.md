# Portfolio — Janis Kamwa

Portfolio multipage en français, basé sur le modèle `Personal` fourni, avec ses bibliothèques d'animation et l'écriture/effacement automatique des métiers.

## Pages
- `index.html` — accueil animé avec Typed.js
- `about.html` — présentation
- `skills.html` — compétences et auto-évaluation
- `portfolio.html` — projets
- `shopminder.html`, `greenfood.html`, `nextravel.html` — études de cas (les liens NexTravel du portfolio ouvrent directement l’application en ligne)
- `resume.html` — formation et expériences
- `services.html` — domaines d'intervention
- `contact.html` — coordonnées et contact par e-mail

## Lancer en local
Ouvre `index.html` dans un navigateur. Pour tester toutes les pages et les ressources comme sur un serveur, utilise Live Server dans VS Code ou un serveur HTTP statique.

## Publier sur GitHub Pages
1. Crée un dépôt public, par exemple `janis-kamwa-portfolio`.
2. Envoie le contenu de ce dossier à la racine du dépôt (pas le dossier parent).
3. Ouvre **Settings → Pages**.
4. Choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis enregistre.
5. Attends la fin du déploiement et ouvre l'URL donnée par GitHub Pages.

## Points à confirmer avant publication
- Vérifier que les liens de démonstration ShopMinder et GreenFood sont toujours accessibles.
- Confirmer que `sitereact-psi.vercel.app` correspond bien à la version actuelle de GreenFood.
- Préciser les technologies réellement utilisées pour ShopMinder et NexTravel et ajouter les dépôts si publics.
- Vérifier les dates exactes de l'expérience de livraison.
- Le CV joint est la version transmise et peut être remplacé par une version plus récente.
- Vérifier si tu souhaites publier ton numéro de téléphone et ton adresse e-mail.

## Confidentialité
Le site affiche l'adresse e-mail et le numéro de téléphone issus du CV. Vérifie que tu souhaites les rendre publics. La page Contact utilise un lien `mailto:` ; elle n'envoie pas les messages via un serveur et n'enregistre aucune donnée.

## Dépendances
Le dossier conserve les ressources du modèle fourni : Bootstrap, Bootstrap Icons, AOS, Typed.js, Swiper, GLightbox, PureCounter, Waypoints, Isotope et ImagesLoaded.
