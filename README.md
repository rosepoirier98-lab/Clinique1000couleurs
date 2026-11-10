# Aux Mille Couleurs — site Web

Site statique prêt pour GitHub Pages.

## Structure
- `index.html` : accueil
- `evaluation.html` : processus d’évaluation
- `equipe.html` : équipe et biographies
- `tarifs.html` : tarifs
- `faq.html` : FAQ
- `tsa.html` : à propos du TSA
- `nous-joindre.html` : coordonnées et demande de rappel
- `assets/` : logo et photos

## Configuration à terminer avant d'activer le formulaire

Le formulaire de la page `nous-joindre.html` est préparé pour Formspree et Google reCAPTCHA v3. Remplacer les deux valeurs temporaires dans le HTML :
- `YOUR_FORMSPREE_FORM_ID` par l'identifiant du formulaire Formspree.
- `YOUR_RECAPTCHA_SITE_KEY` par la clé de site reCAPTCHA v3.

Dans Formspree, configurer l'adresse de notification `info@auxmillecouleurs.com`, activer reCAPTCHA et y enregistrer la clé secrète reCAPTCHA. Le formulaire ne doit pas être considéré comme opérationnel tant que ces étapes ne sont pas terminées et qu'un envoi d'essai n'a pas été confirmé.

Aucun changement DNS n'est requis pour ce montage Formspree + reCAPTCHA : conserver les enregistrements Microsoft 365 (MX, SPF, DKIM et DMARC) existants. Ne pas modifier les DNS de messagerie pour configurer le formulaire.

### Attention — conformité Loi 25 avant la mise en service

Formspree est un fournisseur externe. Avant de lui transmettre des noms, numéros de téléphone ou adresses courriel de parents, vérifier où les données sont hébergées et traitées, conclure les ententes nécessaires et réaliser une EFVP si les renseignements sont communiqués ou confiés à un fournisseur situé hors Québec. Ne pas activer le formulaire en production avant cette vérification. La clinique demeure responsable des renseignements confiés à un fournisseur.
