# myApp/package.json
### Objectif
Fichier de configuration standard pour [npm](https://npmjs.org/doc/json.html). Ce fichier contient notamment le nom et la version de tous les modules Node dont dépend votre application. Vous pouvez le modifier manuellement, mais prenez garde à respecter les conventions, autrement le projet risque de ne plus fonctionner.

### Plus d'infos
> [Cet excellent guide intéractif écrit par Nodejitsu](http://package.json.nodejitsu.com) explique comment est structuré un fichier package.json 



<docmeta name="displayName" value="package.json">

```
{
  "name": "monApp",
  "private": true,
  "version": "0.0.0",
  "description": "une application sail",
  "keywords": [],
  "dependencies": {
    "sails": "~0.10.0-rc7",
    "sails-disk": "~0.10.0",
    "rc": "~0.3.3",
    "include-all": "~0.1.3",
    "ejs": "~0.8.4",
    "grunt": "0.4.2",
    "grunt-sync": "~0.0.4",
    "grunt-contrib-copy": "~0.5.0",
    "grunt-contrib-clean": "~0.5.0",
    "grunt-contrib-concat": "~0.3.0",
    "grunt-sails-linker": "~0.9.5",
    "grunt-contrib-jst": "~0.6.0",
    "grunt-contrib-watch": "~0.5.3",
    "grunt-contrib-uglify": "~0.4.0",
    "grunt-contrib-cssmin": "~0.9.0",
    "grunt-contrib-less": "~0.10.0",
    "grunt-contrib-coffee": "~0.10.1"
  },
  "scripts": {
    "start": "node app.js",
    "debug": "node debug app.js"
  },
  "main": "app.js",
  "repository": {
    "type": "git",
    "url": "git://github.com/dude/monApp.git"
  },
  "author": "dude",
  "license": ""
}
```
