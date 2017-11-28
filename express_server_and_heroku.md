Steps for creating express server and deploying to heroku
1.  Create new directory 
2.  create git repo
3.  initiate node project `npm init` (creates package.json)
4.  Create javascript file (i.e. app.js, index.js) and copy/paste starter code from expressjs.com/en/starter/hello-worl.html

`const express = require('express')`
`const app = express()`

`app.get('/', (req, res) => res.send('Hello World!'))`

`app.listen(3000, () => console.log('Example app listening on port 3000!'))` 

5. create .gitignore file `touch .gitignore` and add node_modules
6. Install dependencies
	a. express
	b. cors
	c. etc.
7. start the app
	a. `node app.js` can also use `nodemon .`
8. deploy to heroku	
	a. `heroku create`
	b. `git push heroku master`
