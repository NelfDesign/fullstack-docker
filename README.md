Application client : c'est l'application SPA servie aux utilisateurs. Nous utilisons React, mais cela fonctionnerait exactement pareil pour Angular et Vue. L'Application client utilise Webpack dev server en développement. Il s'agit d'un serveur Node.js qui permet de détecter les changements dans le code source, de recompiler le code et de rafraichir la page du navigateur.

Reverse-proxy : il s'agit du point d'entrée de l'application qui va se charger ici uniquement de répartir les requêtes entrantes entre nos services.

Base de données : nous aurons une base de données MongoDB
