##how to start

```bash
$ npm install
$ npm install -g connect@2.X.X

$ node server.js &
$ node -e "var cnct = require('connect'); var port = 8080; cnct().use(cnct.static(global.process.env.PWD)).listen(port); console.log('Server has started at http://localhost:' + port);" &

$ open http://localhost:8080/index.html
```
