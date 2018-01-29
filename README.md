# Ruby_on_Rails


## Get

_get_: si l'utilisateur va sur articles, le controller va renvoyer la liste de tous les articles grâce à la méthode get. Si remplissage du formulaire par example : (nouvel utilisateur, nom, email etc) le formulaire va envoyer un data = *post* , quand le formulaire est soumis, c'est une autre méthode. (AKA on est en train de poster)


## database

**La database** = la base de données, dans laquelle le model va chercher et trier les données qu'ils l'intéresse pour le renvoyer au controller (dans le schéma MVC)

## CRUD

**CRUD** = *create, read, update, destroy* = comment faire pour intéragir de manière simple avec notre base de donnée mais par le biais du front-end via notre site. 
Pour avoir son CRUD : resources :articles sur le controller puis rails routes sur la commande et on a le CRUD complet sur le model Articles.

##  I. Différence entre site statique et site dynamique

Un site statique est composé de pages fixes, qui ne changeront pas quelque soit l'utilisateur. Un site dynamique sera présenté de façon différente selon l'interaction avec le visiteur. Les informations présentées ne sont pas les mêmes selon les requêtes de l'internaute. Par exemple twitter / facebook sont des sites dynamiques et un site de restaurant avec juste l'adresse, le menu, des photos du restau est un site statique.

Dès qu'il y a un compte utilisateur, possibilité de commenter, ou de poster des choses par exemple, c'est un site dynamique.

## II. Le MVC 

**Model View Controller** : C'est un modèle utilisé par Rails ou par d'autres languages comme PHP pour montrer une application web.

_On peut l'expliquer grâce à une image. Voici le chemin de la requête : l'utilisateur va sur le site, en fonction de ce qu'il demande au site, comment il se connecte dessus, le site va aller sur le routeur et va demander une fonction, une méthode du controlleur. Le controlleur reconnait la méthode, demande au modèle les informations nécessaire dans la database. Le model renvoit ces informations au controlleur, qui fait le lien avec la view, c'est à dire que le controlleur envoit les informations récupérer à la view, qui va construire la page, la mettre en forme (en HTML et ruby, avec ces informations et renvoyer ce message au controlleur, qui renvoit ça sur le site et à l'utilisateur. _







## III. Les routes 

Les routes permettent d’interpréter les URL et d’orienter vers les bonnes actions des controlleurs. La configuration se trouve dans le fichier config/routes.rb .


