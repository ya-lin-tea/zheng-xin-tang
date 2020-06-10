# zheng-xin-tang

site internet de l'école de thé zheng xin tang

[site de l'école](http://ecoledethe.com)

[Liste des choses que l'on fait](https://github.com/ya-lin-tea/zheng-xin-tang/projects/1?fullscreen=true)

## créer un nouvel article avec vscodium

1. ouvrir vscodium
2. si les fichiers du site n'apparaissent pas, on doit ouvrir le dossier _Zheng Xin Tang_ (soit en cliquant sur _Récent_ ou dans le menu _fichier/ouvrir un dossier_).
3. Pour démarrer à partir d'un modèle, sélectionner _2020-xx-xx-modele_ dans le dossier *_posts* dans la bloc de gauche.
4. on fait une copie du modèle avec un copier/coller (_ctrl-c_ puis _ctrl-v_). 
5. l'action 4 crée un nouveau fichier, en cliquant droit dessus on peut le _renommer_.
6. on peut maintenant écrire l'article, en oubliant pas de renseigner les _meta-données_ (par exemple _author: Ya-Lin_).
7. sauvegarder le document (_ctrl-s_ ou dans le menu _fichier/enregistrer_).
8. ne pas oublier d'enlever : _published: false_ - pour publier l'article

### envoyer sur github pour le publier

- un petit "1" s'affiche tout à gauche sur l'icone _github_. 
- on clique sur l'icone, on renseigne un message pour expliquer la publication puis _ctrl-entrée_
- pour finaliser cliquer sur la petite roue tout en bas à coté du mot _master_. 

## gerer les images

il faut utiliser logiciel krita 

### recadrer l'image

selectioner l'outile de recardrage dans la palet d'outil (crop tool) ou utiliser le racourci: c.

il faut cliquer sur un point d'image et fabriquer une zone avec le pad.

pour valider on appuis sur la touche "retour" ou pour annuler la zone on appuie sur "echap".

### changer la taille de l'image

dans le menu "image" choisir "scal image" 

définir la hauteur (height) ou la largeur (width) et cliquer "ok".

pour le site en paysage c'est à peu près 640x480, en portrait 315x420.

### exporter l'image en jpg

il faut aller dans le menu _file_ et selectioner "export" puis on choisi un l'emplacement et un nom.

### ajouster le niveau ou le contraste

pour améliorer la netteté ou les couleurs avant de retailler l'image, on va dans le menu "filter" puis _adjust contrast_ et on prend l'option _levels_. On clique sur "automatique".

pour les contrastes on peut utiliser l'option "auto contrast".

## inserer image dans un article

1. selectioner l'image dans le dossier _/images_ dans le bloc de gauche
2. bouton droit _copier le chemin d'accès relatif_
3. dans l'article à la place voulue inserer une boîte carrée, une boîte ronde avec un ! devant. 
4. coller (_ctrl-v_) le chemin dans la boite ronde
5. ajouter un / avant l'image

```
![chaxi](/images/2020-05-30-chaxi.jpg)
```

## un peu de Markdown

```
# titre - les thés
## s-titre - les thés verts
### s-s-titre - LongJing

Paragraphe

- liste
- liste1

1. azert
2. qwert

pour mettre en _italique_ en **gras**

- Les liens :

[Qwant](https://www.qwant.com)


- pour les images

![Qwant](/images/2020-05-30-chaxi.jpg)

```
![Qwant](/images/2020-05-30-chaxi.jpg)

