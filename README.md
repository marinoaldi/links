# Links

Useful links repository

##  Node.js

* [NPM Vet](https://www.npmjs.com/package/npmvet) - A simple CLI tool to help vet your npm package versions.
* [NCU](https://www.npmjs.com/package/ncu) - A simple CLI for NCU's Information.


##  Auth0

* [Building and Securing a Modern Backend API](https://scotch.io/tutorials/building-and-securing-a-modern-backend-api) - Learn how to easily manage and secure your API endpoints with Auth0 - Ejemplo bastante interesante. Tienen 3 proyectos, 1 de ellos actua como API y los otros 2 como clientes de la api (User y Admin) con diferentes Scopes para definirles así los permisos. [Github Code](https://github.com/scotch-io/building-and-securing-a-modern-backend-api)

* [Understanding Sessions & Cookies](https://auth0.com/docs/videos/session-and-cookies) - Explains [How to save and retrieve session from Redis](http://stackoverflow.com/questions/14014446/how-to-save-and-retrieve-session-from-redis) using [connect-redis](https://www.npmjs.com/package/connect-redis)

## Cryptography

* [How to generate random SHA1 hash to use as ID in node.js?](http://stackoverflow.com/questions/9407892/how-to-generate-random-sha1-hash-to-use-as-id-in-node-js/14869745#14869745) - I'd recommend using crypto.randomBytes. It's not sha1, but for id purposes, it's quicker, and just as "random".
```javascript
var crypto = require('crypto');
var id = crypto.randomBytes(20).toString('hex');
//=> bb5dc8842ca31d4603d6aa11448d1654
```

##  Utils Online

* [JSON Formatter & Validator](https://jsonformatter.curiousconcept.com/)
* [AVRO Scala Generator](http://avro4s-ui.landoop.com/) - Generate Scala from Avro and Avro from JSon
