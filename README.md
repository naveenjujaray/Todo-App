# Todo App ![react](https://img.shields.io/badge/React.js-16.2.0-blue) ![license](https://img.shields.io/github/license/naveenjujaray/Todo-App?style=plastic) ![forks](https://img.shields.io/github/forks/naveenjujaray/Todo-App?color=violet&label=Forks&style=plastic) ![Stars](https://img.shields.io/github/stars/naveenjujaray/Todo-App?color=yellow&label=Stars&style=plastic)
 **[Remake From]**

![Sample](src/todoapp.gif)

### Features
- Create a task
- Mark as completed
- Delete a task
- Data saved through local storage 💾

To view a live example, [click here]

### Getting Started
In-order to work with this repo you will need to install Node.js on your machine.
```
# Clone this repository
$ git clone https://github.com/naveenjujaray/Todo-App.git

# Go into the repository
$ cd Todo-App

# Get Packages
$ npm install

# Launch/View
$ npm start
```
### Deployment 📦
When you are done with the setup, you should host your website online. We highly recommend to read through the docs for [ReactApp] Hosting.
```
# Install the gh-pages package as a “dev-dependency” of the app
$ npm install gh-pages — save-dev

# Add homepage property to package.json file below "private": true,
$ “homepage”: “http://{Github-username}.github.io/{Github-repo-name}"

# Deploy scripts under package.json file
$ “scripts”: {
    "start": "react-scripts start",
    “predeploy”: “npm run build”,
    “deploy”: “gh-pages -d build”,
    "build": "react-scripts build",
    }

#  Create a remote GitHub repository (Skip this step if your remote GitHub repository is already initialized)
$ git init
$ git remote add origin your-github-repository-url.git

# Now deploy it to GitHub Pages
$ npm run deploy
```

[Remake From]: https://github.com/alyssaxuu/todo-app
[ReactApp]: https://create-react-app.dev/docs/deployment/
[click here]: https://naveenjujaray.github.io/Todo-App/