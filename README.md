Play Cosmo Note
==================================

- Basic REST API server


Default config.json file
==================================

> Place config.json in 'src' directory

- macos
```
{
	"port": 8010,
	"gethPwd": "/Users/youruser/Library/Ethereum/testnet/geth.ipc"
}
```
- ubuntu
```
{
	"port": 8010,
	"gethPwd": "/users/myuser/.ethereum/geth.ipc"
}
```

Console output standard
==================================

```
    > what we send
            console.log(`> pong: ${message}`);
            ws.send(`pong: ${message}`);
    = internal 
            console.log(`= message: ${message}`);
    
    < what we get
            
    
```

Express & ES6 REST API Boilerplate
==================================

[![bitHound Score](https://www.bithound.io/github/developit/express-es6-rest-api/badges/score.svg)](https://www.bithound.io/github/developit/express-es6-rest-api)

This is a straightforward boilerplate for building REST APIs with ES6 and Express.

- ES6 support via [babel](https://babeljs.io)
- REST resources as middleware via [resource-router-middleware](https://github.com/developit/resource-router-middleware)
- CORS support via [cors](https://github.com/troygoode/node-cors)
- Body Parsing via [body-parser](https://github.com/expressjs/body-parser)

> Tip: If you are using [Mongoose](https://github.com/Automattic/mongoose), you can automatically expose your Models as REST resources using [restful-mongoose](https://git.io/restful-mongoose).


Getting Started
---------------

```sh
# clone it
git clone git@github.com:developit/express-es6-rest-api.git
cd express-es6-rest-api

# Make it your own
rm -rf .git && git init && npm init

# Install dependencies
npm install

# Start development live-reload server
PORT=8080 npm run dev

# Start production server:
PORT=8080 npm start
```

License
-------

MIT
