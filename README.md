# Links

Useful links repository

##  Node.js

### Versions / Releases
* [Node.js Releases](https://nodejs.org/es/download/releases/)
* [node.green](http://node.green/) - Node.js ECMAScript compatibility tables

### Utils
* [NPM Vet](https://www.npmjs.com/package/npmvet) - A simple CLI tool to help vet your npm package versions.
* [NCU](https://www.npmjs.com/package/ncu) - A simple CLI for NCU's Information.


##  Auth0

* [Building and Securing a Modern Backend API](https://scotch.io/tutorials/building-and-securing-a-modern-backend-api) - Learn how to easily manage and secure your API endpoints with Auth0 - Ejemplo bastante interesante. Tienen 3 proyectos, 1 de ellos actua como API y los otros 2 como clientes de la api (User y Admin) con diferentes Scopes para definirles así los permisos. [Github Code](https://github.com/scotch-io/building-and-securing-a-modern-backend-api)

* [Understanding Sessions & Cookies](https://auth0.com/docs/videos/session-and-cookies) - Explains [How to save and retrieve session from Redis](http://stackoverflow.com/questions/14014446/how-to-save-and-retrieve-session-from-redis) using [connect-redis](https://www.npmjs.com/package/connect-redis)

* How to Integrate REST APIs with Single-Page Apps and Secure Them Using Auth0: [Part 1](https://aws.amazon.com/es/blogs/apn/how-to-integrate-rest-apis-with-single-page-apps-and-secure-them-using-auth0-part-1/), [Part 2](https://aws.amazon.com/es/blogs/apn/how-to-integrate-rest-apis-with-single-page-apps-and-secure-them-using-auth0-part-2/)

* [node-auth0](https://github.com/auth0/node-auth0) - [Recommended way to re-inject renewed token for Management API in a long-running script?](https://github.com/auth0/node-auth0/issues/164)

## Cryptography

* [How to generate random SHA1 hash to use as ID in node.js?](http://stackoverflow.com/questions/9407892/how-to-generate-random-sha1-hash-to-use-as-id-in-node-js/14869745#14869745) - I'd recommend using crypto.randomBytes. It's not sha1, but for id purposes, it's quicker, and just as "random".
```javascript
var crypto = require('crypto');
var id = crypto.randomBytes(20).toString('hex');
//=> bb5dc8842ca31d4603d6aa11448d1654
```

## Static Site Generators (see https://www.staticgen.com/ Top Open-Source Static Site Generators)

* [Phenomic](https://github.com/MoOx/phenomic) - Phenomic is a modern static website generator based on the React and Webpack ecosystem. https://phenomic.io
* [Jekyll](https://github.com/jekyll/jekyll) - Jekyll is a blog-aware, static site generator in Ruby. http://jekyllrb.com
* [Hexo](https://github.com/hexojs/hexo) - A fast, simple & powerful blog framework, powered by Node.js. https://hexo.io 
* [Hugo](https://github.com/spf13/hugo) - A Fast and Flexible Static Site Generator built with love in GoLang http://gohugo.io
* [Gatsby](https://github.com/gatsbyjs/gatsby) - Transform plain text into dynamic blogs and websites using React.js.
* [MkDocs](https://github.com/mkdocs/mkdocs/) - Project documentation with Markdown. http://www.mkdocs.org
* [Bi Sheng](https://github.com/benjycui/bisheng) - Transform Markdown (and other static files with transformers) into a SPA website using React.

### Utils

* [serverless/post-scheduler](https://github.com/serverless/post-scheduler) - Schedule posts & content updates for static websites (Jekyll, Hugo, Gatsby, Phenomic etc) https://serverless.com/blog/static-site-post-scheduler/

## Material Design

* [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material) - A Material Design theme for MkDocs

##  Utils Online

* [JSON Formatter & Validator](https://jsonformatter.curiousconcept.com/)
* [AVRO Scala Generator](http://avro4s-ui.landoop.com/) - Generate Scala from Avro and Avro from JSon
