l'application "todo list" est une petite app crée n utilisant les fonctionnalités de express.js. Celles-ci sont :
  
  - Express : pour créer un server web.
  
  - Cookie session : pour sécuriser les cokies de session de l'utilisateur.
  
  - Body-parser : pour récupérer les paramètres envoyés lors d'une requete "post".
  
  - Middlewares : une collection de fonction à exécuter en ordre pour éviter des problèmes ou faire de l'authentification avant de 
  
  renvoyer la réponse à l'utilisateur.


Express.js est bas niveau et ne permet pas de développer complétement les app web, mais il permet de déléguer plusieurs tâches à d'autre 

framworks ou langages. Ici, on a utilisé le moteur de templates "ejs" pour créer les pages html demandées par l'utilisateur.
