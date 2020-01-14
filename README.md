Rappel du contexte<br />

Création d’un extranet mettant à disposition des ressources pour les salariés  des différentes banques françaises.<br />    
Réalisation :<br /> 
● développement du produit ;<br />  
● présentation de la liste des différents acteurs du système bancaire  français.<br />

Charte graphique<br />

● Wir e f r a m e ​ et ​ z o nin g ​ : fournis par notre webdesigner​.<br />  
● Colorimétrie : choix libre s’accordant avec notre logo​.<br /> 

Particularités du site<br />

● Site responsive : possibilité de consulter le site au bureau ou en  itinérance à partir de différentes supports (tablettes et smartphones).<br />    

Fonctionnalités de l’application<br />

La structure du site sera développée en HTML5, la mise en forme et la mise en  page seront faites en CSS3.<br />  
Le site sera proposé à tous les utilisateurs en situation de mobilité et/ou  sédentarisés dans un bureau. Il est donc impératif de mettre en place au  moins un ​ b r e a k p oin t ​ pertinent.<br />  
La connexion avec la base de données s’effectuera via PDO en PHP.<br />  
Les langages PHP et SQL seront utilisés pour traiter les interactions entre le  site et la base de données.<br />

Connexion/déconnexion<br />

● Connexion requise pour accéder aux informations du site via un UserName  et un Password.<br />  
● Au chargement de la page, les champs UserName et Password prennent  toute la largeur de l’écran, entre le ​ h e a d e r ​ et le ​ f o o t e r​ .<br /> 
● À la première connexion, l'utilisateur peut créer son compte via une page  d’inscription.<br />  
● L’utilisateur peut modifier ses informations personnelles à tout moment via  la page « Paramètres du compte ».<br />  
● Champs requis sur la page d’inscription :<br />  
○ Nom ;<br />  
○ Prénom ;<br />   
○ UserName ;<br />   
○ Password ;<br />   
○ Question secrète ;<br />  
○ Réponse à la question secrète.<br />  
● Si l'utilisateur oublie son mot de passe, il peut saisir son UserName et  répondre à la question secrète pour en créer un nouveau.<br />   
● Quand l’utilisateur est connecté, son nom et son prénom sont indiqués  dans le ​ h e a d e r ​ sur l’ensemble des pages.<br />  
● Un bouton « Se déconnecter » est présent dans le ​ h e a d e r​ .  
● Si l'utilisateur est déconnecté, il est redirigé automatiquement vers la  première page pour une nouvelle connexion via un UserName et un  Password.<br />  

Utilisateur connecté<br />

Sont présents sur la page :<br />  
● présentation succincte du GBAF ;<br />  
● liste des différents acteurs/partenaires du système bancaire français  comprenant :<br />  
  ○ logo ;<br />  
  ○ titre ;<br />   
  ○ présentation de l’entreprise avec affichage de la première ligne de  texte ;<br />  
  ○ bouton « Afficher la suite » (permettant d’ouvrir une nouvelle page  pour chaque acteur/partenaire).<br />
  
Détails de la page partenaire comprenant :<br />

● logo ;<br />  
● titre ;<br />  
● texte de description complet ;<br />  
● bouton Like/Dislike permettant de donner un avis ​ (p r o f e s sio n n el e t  c o n s t r u c tif) ​ en un clic sur l’acteur/partenaire ;  
● indication du nombre de Like/Dislike ;<br /> 
● bouton pour poster un nouveau commentaire ;<br /> 
● liste des commentaires sur cet acteur/partenaire incluant :<br />  
○ le prénom de l’utilisateur qui a laissé le commentaire ;<br />  
○ la date de publication ;<br />  
○ le texte.<br />

Informations complémentaires​ : pour chaque nouveau commentaire, le prénom  (de la personne connectée) et la date (du jour) seront remplis automatiquement.<br />  
