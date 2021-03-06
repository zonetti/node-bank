<p align="center">
  <img src="https://raw.githubusercontent.com/nulldreams/node-bank/master/box.png" alt="Size Limit example"
       width="20%" height="20%">
</p>
<h4 align="center">A <a href="https://www.nubank.com.br/" target="_blank">Nubank</a> API in NodeJS</h4>
<p align="center">
  <a href="https://gitter.im/simple-apis/node-bank"><img src="https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg"></a>
	
  <a href="https://saythanks.io/to/nulldreams">
      <img src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg">
  </a>  
	
  <a href="https://github.com/nulldreams/node-bank/issues">
      <img src="https://img.shields.io/codeclimate/issues/github/me-and/mdf.svg">
  </a>

  <a href="http://makeapullrequest.com">
      <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square">
  </a>
</p>
<p align="center">
  <a href="#routes">Routes</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
</p>

## Routes
* **`POST /user/:token`**
send a json
```json
{
	"cpf": "__cpf",
	"pass": "__pass"
}
```
and get the token in `access_token`
```json
{
    "response": {
        "access_token": "__token",
        "token_type": "bearer",
...        
```

* **`GET /bill/:token`**
```json
{
   "data": {
       "return your bills"
   }
}
```

* **`GET /purchases/:token`**
```json
{
   "data": {
       "return your purchases"
   }
}
```

* **`GET /me/:token`**
```json
{
   "data": {
       "return your resumed info"
   }
}
```

* **`GET /account/:token`**
```json
{
   "data": {
       "return your complete info"
   }
}
```

* **`GET /events/:token`**
```json
{
   "data": {
       "return your events"
   }
}
```

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/nulldreams/node-bank.git

# Go into the repository
$ cd node-bank

# Install dependencies
$ npm install

# Run the app
$ npm start
```

## Credits

This software uses some open source packages.

- [Node.js](https://nodejs.org/)
- [Fastify](https://github.com/fastify/fastify)
- [Request](https://github.com/request/request)

**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

---

> GitHub [@nulldreams](https://github.com/nulldreams) &nbsp;&middot;&nbsp;
