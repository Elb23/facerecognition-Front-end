J'ai utilise plusieurs composants et librairies dans le front End.

L'objectif est d'authentifier les utilisateurs en toute securite, chaque utilisateur a un email unique, 
Le nombre de recherches incremente, chaque recherche fait appel a un api qui detecte les visages.

Il y a plusieurs API dans Clarifai, et on peut simplement changer de model si l'on veut changer de type de recherches,
selon le model entraine que l'on veut(detection de visages, d'objets, de couleurs etc..)

L'utilisateur a besoin de s'enregistrer d'abord et ensuite de taper le bon mot de passe avant de pouvoir se connecter.
Toute la gestion des mots de passes est dans la backend, les mots de passes sont stockes dans la base de donnee
le front end fait des appels au backend, qui lui fait des appels a la base de donnees en le mot de passe est crypte 

Voir readme backend

Pour toute question contactez-moi sur eb.abdelhadi@gmail.com
