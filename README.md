# Déménagements Christophe — refonte du site

Site vitrine one-page de [Déménagements Christophe](https://www.christophe-demenagements.com/), Les Gentlemen du Déménagement à Reims.

Un seul fichier `index.html` (HTML, CSS et JS inclus, aucune dépendance), accompagné des 21 photos en WebP. Ouvrir `index.html` dans un navigateur suffit.

## Contenu

- Animation d'accueil (SVG + JS, 8 s, jouée à chaque chargement de la page)
- Estimateur rapide de volume, 3 types de voyages, formules particuliers et entreprises
- International et DOM-TOM, garde-meubles, piano et coffre-fort, monte-meubles, matériel
- Fiche inventaire complète avec calcul du volume et sauvegarde locale
- Boutique et conseils d'emballage, norme ISO 9001 / 14001, avis, contact

## Avant la mise en ligne

1. Renseigner `data-endpoint` sur `#contactForm` et `#invForm` (Formspree ou route API, POST JSON `{_subject, email, message}`). Sans endpoint, les formulaires ouvrent la messagerie du visiteur.
2. Poser les redirections 301 depuis les anciennes URLs (liste en commentaire en tête de `index.html`).
3. Recréer les pages mentions légales et politique de confidentialité, encore liées à l'ancien site.

## Hébergement

GitHub Pages fonctionne tel quel : Settings → Pages → branche `main`, dossier `/ (root)`.
