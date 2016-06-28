# lean-code-template

A barebones static html app using [Express 4](http://expressjs.com/).

## Prerequisities

1. You need to install [Node.js](http://nodejs.org/)
2. You need a code editor e.g. [Sublime Text](https://www.sublimetext.com/)
3. You have cloned this/your custom repository to a local folder
4. You've installed the [heroku toolbelt](https://toolbelt.heroku.com)

## Running Locally

```sh
npm install
npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

All HTML/CSS/JS files are in the `public` directory, anything stored in `public` will be served statically to the user.

## Deploying

This repository is setup to allow for quick deployment to [Heroku](https://heroku.com)

To setup an app on heroku:
```sh
heroku login #(will ask for username and password)
heroku create your-app-name
```

To deploy your latest changes:
```sh
git commit -am "Short message explaining the changes I've made"
git push heroku master
```

Your site will be live at https://your-app-name.herokuapp.com
