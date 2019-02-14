![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 38: Socket.io Basics

### Author: Becca Lee
Paired some with Heather Cherewaty

### Links and Resources
* [front-end repo](https://codesandbox.io/s/4lxn9515x7)
* [front-end url](https://4lxn9515x7.codesandbox.io/)
* [back-end repo](https://github.com/beccalee123/37-login-auth/blob/master/README.md)

### Modules
## Back End Repo:
- `server.js` runs the server

## Front End Repo
- `index.js` renders the main app
- `app.js` renders the Troll component
- `troll.js` contains the core app functionality, including state, methods, socket.io calls, and rendering functions
- `styles.css` contains the app styling
- `__tests__/` contains the testing suite

#### Running the app
* To run the app, clone the backend repo, and run an `npm i` in your console. Then run `nodemon`
* From there, the app can be run using the front-end url linked above.
* You may open the front end app in multiple windows and see the chat in all windows
  * Note: if you refresh the page or leave the page, your chat will be lost
  
* If you wish to work with the code, simply fork the repo and jump right in
  
#### Tests
Testing currently covers the core functionality of the front-end app, including the existance of specific elements after certain actions and the changing state