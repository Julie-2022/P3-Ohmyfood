Attention : I am a student, may contain errors...
Working progress :) 

# Ohmyfood

1. Télécharger Node js
2. git init : compte GitHub
3. npm init : pour créer package.json
4. npm install sass : pour installer sass et créer le dossier "node_module" et "package-lock.json"
5. Créer un espace indépendant "devDependencies" (pour que sass ne soit pas envoyé sur GitHub à chaque fois 
et donc libérer de l'espace
6. Ajouter un fichier : .gitignore pour y mettre "node_modules" et ainsi ne pas les importer à chaque push/gitHub
7. sass -v : pour vérifier s'il y est 

En cas de souci : 
1. Suppr Node-modules + package-lock.json
2. npm remove sass
3. npm install sass
4. sass -v
5. sass style.scss style.css (aprés avoir créer 1 fichier scss nommé : style.scss)
==> création de Node-modules + package-lock.json + style.css.map

Grace au script dans package.json (ligne 7) : "sass": "sass style.scss style.css" 

=> on peut utiliser : npm run sass pour compliler en auto (Ctrl-C to stop)

Cloner le projet de quelqu'un d'autre :
1. git clone
2. npm install
3. npm run "nom du script dans package.json"


Pendant le projet pour envoyer sur GitHub :
1. git add --all && git commit -m "explication étapes réalisées"
2. git push

