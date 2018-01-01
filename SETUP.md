bash commands:
```bash
$ npm config list
$ npm set init.author.name "Ryan Wibawa"
$ npm set init.author.email "ryan.wibawa@gmail.com"
$ npm set init.author.url "https://rwibawa.github.io/"
$ npm config list

$ npm adduser
# username: rwibawa
# email: ryan.wibawa@gmail.com

$ git clone git@github.com:brentertz/scapegoat.git
$ cd scapegoat/

$ git remote -v
$ git remote set-url origin https://github.com/rwibawa/scapegoat.git
$ git status
$ git add .
$ git status
$ git commit -m "initial commit"
$ git push -u origin master

$ npm install mocha --save-dev
$ npm install chai --save-dev
$ sudo apt-get install tree
$ tree node_modules/

$ npm test

$ git tag 0.1.0
$ git push origin master --tags

$ npm install git://github.com/rwibawa/scapegoat.git
$ npm install git://github.com/rwibawa/scapegoat.git#0.1.0
$ npm install . -g
$ npm ls -g

$ node
> var escape = require('scapegoat').escape;
> escape('<h1>Hello world!</h1>');
> .exit

$ npm publish
$ npm install scapegoat

```
