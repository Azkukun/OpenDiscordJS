# OpenDiscordJS
OpenDiscordJS is a plugin for a basic and simple JS. The first official version is a FrenchAcacia 1.2.4.


# FrenchAcacia 1.2.4

The French Acacia is in dev'. But the Project is now here : 2s PLEASE

# EnglishAcacia 1.2.4
The English acacia is found ! But... The translate is bad... In dev':3

# New ! 
(FR) Une ancienne version de OpenDiscordJs (SimpleJs) est là !
C'est la Cookie 0.0.1 !
___________________________

PLEASE DON'T USE THIS VERSIONB FOR A REAL BOT
THIS IS A UNSTABLE VERSION 
THIS VERSION IS FOR THE JOKE :3

Cookie 0.0.1
=========
By Azkun and meniro

Exclusivement, la Cookie 0.0.1 est là durant pas très longtemps..  
Download
=========
Pour téléchager simplejs, dans votre index.js (Création d'un bot sur le create.MD),puis ecriver ceci (maj dispo, revenez donc voir cela parfois) :

 let command = message.content.split(" ")[0].slice(prefix.length).toLowerCase();
  
let args = message.content.split(" ").slice(1);

const mc = message.content

const cmds = message.content === prefix

  const sjsping = prefix + "ping"
  
const sjscredits = prefix + "credits"
Commencer
=========
utilisez `const prefix "le prefix du  bot"` puis `const sjsping = prefix + "ping"` pour definir correctement ping puis, ecrivez if(message.content === sjsping){ , sauter une ligne, ecriver `var ping = new Date().getTime() - message.createdTimestamp;` puis faites `message.reply("Pong ! " + ping + "ms.")`, ensuite sauter une ligne, et faites }. puis ajouter 1 au watch.json voila pour le setup, ecrivez en mp dans le bot le prefix du bot ping, si il vous repond, c bon ! SJS est download ! Sinon, contactez Azkun#1930 sur discord !

Utilisez d'abord dans bot.on('message', message => { //Le download //ici }); `cpingHead` 

Raccourcis
=========
bienvenue dans la premiere partie de la documentation : raccourcis code, ils servent a aller beaucoup plus vite . exemple, `sjsping` qui servent a créé une commande ping disant "pong ! 0ms" en changeant 0 par le ping du bot.
Voici une petite liste des raccourcis du bot

#À noter que cette version est sûrement instable.
