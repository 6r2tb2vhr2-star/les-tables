MES TABLES — application personnelle gratuite

CONTENU
- index.html : application web (carte + recherche + notes)
- manifest.json et icones : installation ecran d'accueil

UTILISATION ET MISE EN LIGNE GRATUITE
1. Cree un compte GitHub gratuit : https://github.com/
2. Cree un nouveau depot (repository) PUBLIC, par exemple "mes-tables".
3. Depose index.html, manifest.json, icon-192.png, icon-512.png a la racine du depot.
4. Dans Settings > Pages : Deploy from a branch, branche main et dossier /(root), puis Save.
5. Attends la publication indiquee par GitHub et ouvre le lien Pages fourni.
6. Sur iPhone : Safari > bouton Partager > Sur l'ecran d'accueil.

PRIVACITE
- Le code de l'application est visible car GitHub Pages gratuit exige un depot public.
- Tes evaluations ne sont pas envoyees vers GitHub : elles sont stockees dans ton navigateur (localStorage).
- Chaque navigateur/appareil garde un carnet distinct : aucun compte, aucune synchronisation.
- Utilise "Sauvegarder mes notes" regulierement et garde le fichier JSON.
- Supprimer les donnees du site ou changer d'appareil peut effacer le carnet local.
- Les requetes pour trouver des restaurants vont aux serveurs publics d'OpenStreetMap/Overpass.

LIMITES
- Internet indispensable pour afficher la carte et rechercher des restaurants.
- Les restaurants proviennent d'OpenStreetMap, base collaborative, potentiellement incomplete.
- Les serveurs publics peuvent etre indisponibles / restreindre les requetes.
- La recherche par nom couvre un rayon de 25 km autour du centre de la carte.
- Pour une autre ville : choisis-la dans la liste ou navigue sur la carte.
- Aucun frais recurrent ou paiement requis dans cette configuration pour un usage personnel leger.

LICENCES / SERVICES
- Fond cartographique : © OpenStreetMap contributors, https://www.openstreetmap.org/copyright
- Donnees restaurants : OpenStreetMap via Overpass API, https://wiki.openstreetmap.org/wiki/Overpass_API
- Bibliotheque cartographique : Leaflet 1.9.4, https://leafletjs.com/

IMPORTANT : ce prototype n'est pas heberge automatiquement. Un deploiement GitHub Pages reste a faire.
