![](https://lh4.googleusercontent.com/-PVw-ZUM9vV8/UuWeH51os0I/AAAAAAAAD6M/0Ikg7viJftQ/w1286-h566-no/hackathon-starter-logo.jpg)

Hackathon Starter
=======================
Ceci est une trousse de démarrage pour le hackathon de Radio Canada.

### Prerequis
- Compte Azure (https://azure.microsoft.com/en-us/free/)
- App ID pour les réseau sociaux
- Accès fonctionnel pour les API de Radio Canada

#### Si vous désirez faire du réseau sociaux
###### Pour obtenir un Facebook APP ID (https://developers.facebook.com/apps)
- Pour les étapes vous pouvez consulter les screenshots via /screenshots/Facebook_AppID/
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/8i9p3D854O4/0.jpg)](http://www.youtube.com/watch?v=8i9p3D854O4)

###### Pour obtenir un Twitter APP ID (https://apps.twitter.com/)
- Pour les étapes vous pouvez consulter les screenshots via /screenshots/Twitter_AppID/
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/9ckccMDhtQI/0.jpg)](http://www.youtube.com/watch?v=9ckccMDhtQI)

###### Pour obtenir un Instagram APP ID (https://www.instagram.com/developer/)
- Pour les étapes vous pouvez consulter les screenshots via /screenshots/Instagram_AppID/
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/EZ6_1mm11kg/0.jpg)](http://www.youtube.com/watch?v=EZ6_1mm11kg)

### API Radio Canada
- Neuro (http://services.radio-canada.ca/neuro/v1/documentation)
- MediaNet 
- Picto

### Example consommation Neuro
> http://services.radio-canada.ca/neuro/v1/future/lineups/{lineupId}

#### Example de line up

Line up ID | Nom
--- | --- 
131270 | Ppage - Une - Région - Grand Montréal
117812 | Économie
117814 | Famille
117815 | Histoire
117816 | Humour
117820 | Politique
92411 | Justice - À la une
4165 | Science - À la une
4167 | Arts - À la une
4169 | Techno - À la une

#### Example consommation MediaNet
> Par example pour une nouvelles : 
> http://services.radio-canada.ca/neuro/v1/news-stories/1005274
> Vous allez retrouver sous summaryMultimediaContent un selflink qui est 
> http://services.radio-canada.ca/neuro/v1/media/7647781
> Pour connecter le player medianet
> 

#### Example consommation Picto
> http://images.radio-canada.ca/v1/ici-info/1x1/lucie-charlebois-ministre.png

### Contact
Pour plus d'information vous pouvez contacter :
- Viet Nguyen (mailto: quoc-viet.nguyen@radio-canada.ca)
- Hugo Leclerc (mailto: hugo.leclerc@radio-canada.ca)
- Dominic Fortin (mailto: dominic.fortin@radio-canada.ca)