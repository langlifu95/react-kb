

# React Kanban

### Tech stack

* [React](https://github.com/facebook/react)
* [Redux](https://github.com/reactjs/redux)
* [React-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd)
* [Sass](https://github.com/sass/sass)
* [Webpack](https://github.com/webpack/webpack)
* [Babel](https://github.com/babel/babel)
* [Express](https://github.com/expressjs/express)
* [MongoDB](https://github.com/mongodb/mongo)
* [Passport](https://github.com/jaredhanson/passport)


### Development

Setting up the full app with your own mongoDB instance and auth credentials for Twitter and Google sign-in requires significant effort. Use the simplified set up if you don't want to bother with that.

#### Simplified setup

```shell
# Clone the simple-dev branch which does not include db and social sign-in stuff
git clone https://github.com/yogaboll/react-kanban.git -b simple-dev

cd react-kanban

npm install

npm run build

# Open a second terminal window and run:
npm run serve
```

The app will run on http://127.0.0.1:1337
