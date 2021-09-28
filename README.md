
# FiveM-Server

Small package in order to interact with FiveM API

**How-to install :**

```
npm i fivem-server
```

**How-to use :** 
Here is an example to display the number of players online on a server.

```js
const myIp = "11.111.111.111:30120"
const  fivem_server =  require("fivem-server");
const  fivemApi  =  new  fivem_server(myIp)
```



```js
fivemApi.getAllInfo()
.then(console.log)
.catch(console.log)
```



**players mehtods:**
```js
fivemApi.getPlayers()
.then(console.log)
.catch(console.log)
```

**methods**

 >  - getAllInfo() 
       >  - getName()
       >  - getResources()
       >  - getIcon()
       >  - getBanner_connecting()
       >  - getBanner_detail()
       >  - getPlayers()
       >  - getPlayersCount()

completing ..