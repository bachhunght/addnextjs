# Custom Express Server example

## How to use

### Creer une nouvelle page template
-> dans wordpress :
-> creer un nouveau fichier php dans wp-content/themes/api/contact.php
-> ajouter le nom du theme : <?php /* Template Name: contact */ ?>

-> dans nextjs :
-> creer un nouveau fichier js dans pages/page/contact.js


creer un fichier de variable d'environnement : .env 

```
# Host
API_HOST="http://api.demepool.local"
FRONT_HOST="http://localhost:3000"
FRONT_DOMAIN="localhost"

# Google Tag Manager
GTM_ENABLE=false
GTM_ID="GTM-XXXXXXX"

# Google reCaptcha
RECAPTCHA_ID="6LeIxAcTAAAAAJcZVRqyHh71UMIEGNQ_MXjiZKhI"

# api référentiel géographique
GOUV_API="https://geo.api.gouv.fr"

# google map api
GOOGLE_MAPS_KEY=""
GOOGLE_MAPS="https://maps.googleapis.com/maps/api/js?v=3"
```
