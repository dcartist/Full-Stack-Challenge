# FULL-STACK CHALLENGE

You will be creating a front-end with the API that you created in the backend challenge. You can use HTML/CSS, EJS, REACT JS, Django or Flask. 

## Requirements

Your project must satisfy the following requirements:

- Be built using HTML/CSS, EJS, REACT JS, Django or Flask.

- Must be able to do full CRUD from the front end.

- Runs without errors

- It must be mobile-friendly

- Must have an about page where it talks about the project and how to maneuver through your project

- Have a repository under your GitHub account (do not fork this repo).

- You can use Bootstrap, Bulma, Tailwind CSS, Material UI, Semantic UI, etc. 

- Be deployed to Heroku, Netlify, Github, or Vercel (**THIS IS REQUIRED**)

- Have good, clean code with comments on what is happening throughout your code. Use the auto-formatter regularly!

- Demonstrate a good commit history. The more commits you make, the better it is for you when something goes wrong.

- Must have a well-document README (**THIS IS REQUIRED**)

- - A description of your project. Basically, what is it, and what does it do.
  - A README must have instructions on how to install and run your project locally.
  - A list of technology used in your project

## FAQ

**Do I need to do full CRUD?**

Yes, you must be able to do **FULL CRUD** from the front end. You can use axios or fetch to help with those API calls.

Axis cheatsheet: https://kapeli.com/cheat_sheets/Axios.docset/Contents/Resources/Documents/index

**Why am I getting CORS errors?**

You have cross-browser issues, and the only way to solve it is to make sure your API has CORS to allow others to use it.



**For Express**:

https://www.npmjs.com/package/cors

```
npm i cors
```

Keep `app.use(cors())` to the top of your api

```javascript
var express = require('express')
var cors = require('cors')
var app = express()

app.use(cors())
//rest of the code
```



**For Flask**:

https://flask-cors.readthedocs.io/en/latest/

**For Django**:

- https://www.stackhawk.com/blog/django-cors-guide/
- https://github.com/adamchainz/django-cors-headers



**What if my API is missing routes that I need for my front end to work properly?**

Then adjust your API to work the way you want it to.

**What if I suck at design?**

Look at websites, find a design you like, and try to mock the design. Plan it out; you got this! Here are two links to lists of excellent sites.

- [https://www.webdesign-inspiration.com](https://www.webdesign-inspiration.com/)
- [https://www.awwwards.com](https://www.awwwards.com/)

