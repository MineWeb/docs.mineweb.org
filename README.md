<p align="center">
  <img src="https://mineweb.org/favicon.png" alt="MineWeb">
</p>

<p align="center">Documentation du CMS MineWeb.</p>

<p align="center"><img src="https://dl.dropboxusercontent.com/u/95847291/github%20images/slate/slate_screenshot_new.png" width=700 alt="Screenshot of Example Documentation created with Slate"></p>


Présentation
------------

La **documentation** de mineweb.org regroupe toutes les informations nécessaires au bon fonctionnement du CMS **MineWeb** ainsi que des tutoriels sur la création d'extensions ou sur la liaison avec le serveur.
Ce repo vous permet de contribuer à la documentation grâce au système de Pull-Request de Github permettant ainsi à la documentation d'être plus complète. La documentation est au format [Markdown](https://fr.wikipedia.org/wiki/Markdown) et utilise la librairie [Slate](https://github.com/lord/slate). 

Comment contribuer ?
------------------------------

Nous vous remercions de votre contribution. Veillez à faire le moins possible de fautes aussi bien de français que dans vos informations. Votre contribution sera bien sûr vérifiée avant d'être validée

## Cloner et modifier

Il vous faut tout simplement cloner ce repo, et faire vos modifications directement dans `source/`. 

### Comment éditer une section

Pour éditer une section déjà présente sur le CMS il vous suffit d'éditer le fichier de la section correspondante se situant dans `source/includes`.

### Comment ajouter une section

Pour ajouter une section, il vous suffit de rajouter un fichier `source/includes/` au format `_{Nom de la section}.md`. Il faudra également ajouter le nom de votre section dans le fichier `source/index.html.md` dans la liste `includes`.
Il vous suffira ensuite de remplir la section comme vous le souhaitez. 
