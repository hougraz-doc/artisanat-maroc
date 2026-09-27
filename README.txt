# Artisanat Maroc — site pédagogique

Site HTML/CSS/JS correspondant au TP n°1 « Analyse des données web ».

## Fichiers
- index.html : page principale avec les éléments ciblés par le TP.
- css/style.css : design responsive.
- js/script.js : interactions de démonstration.
- catalogue.pdf : PDF local pour tester le téléchargement.

## Éléments GTM prévus
- ID du bouton : `btn-devis`
- ID du formulaire : `form-contact`
- ID du lien PDF : `dl-catalogue`
- Événement GA4 demandé par le TP pour le devis : `generate_lead`
- Événement GA4 demandé par le TP pour le formulaire : `form_submit`

## Installation GTM
Dans `index.html`, décommentez les deux blocs GTM et remplacez `GTM-XXXXXXX`
par votre identifiant de conteneur. Le reste de la configuration se fait dans GTM.
