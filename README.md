Mini app de visualisation de notices d'unicas Sudoc basée sur Angular. 

Le dépôt contient un fichier de données d'exemples sous Excel dans /data (données réelles des unicas du Centre Régional PACA/Nice, avril 2018). La méthode d'obtention des données en amont est décrite ici 
Le fichier est converti à la volée en json avec la librairie js.xslx (/lib)

Pour personnaliser l'app avec vos données :

* mettre votre GOOGLE_API_KEY dans index.html

* lier l'appli à vos données : déposer votre fichier data.xslx dans /data. Vous pouvez le nommer autrement ou le déposer ailleurs, mais il faudra modifier le chemin relatif d'accès dans index.html
