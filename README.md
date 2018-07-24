# derpy.js
Official node.js wrapper for the ohlookitsderpy.space API

**Installation**

``npm install derpy.js`` 

**Example**

```js
const derpy = require("derpy.js");

derpy.miku().then(res => console.log(res)).catch(err => console.log(err));

```

**Methods**

``.miku()`` - Get a random Miku wallpaper

``.ddlc()`` - Get a random DDLC wallpaper

``.lovelive()`` - Get a random Love Live gif

``.k_on()`` - Get a random K-On gif

``.takagi()`` - Get a random Takagi-san image

``.nekoparastatic()`` - Get a random Nekopara image (NSFW)

``.nekoparagif()`` - Get a random Nekopara gif (NSFW)


**Credits**

August for updating stuff TM
