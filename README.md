# FiveM-Api
C'est une api pour intéragir avec le petite api FiveM

**Pour l'installer :**
```
npm i fivem-api
```
**Pour l'utiliser :**
Ex, pour afficher le nombre de joueurs sur un serveur : 
```javascript
const fivem = require("fivem-api");
fivem.getServerInfo("185.223.30.29:30120").then((server) => console.log(server.players.length))
```

la fo
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjk2MDE2MTM0LDEzNjY3ODMxMTNdfQ==
-->