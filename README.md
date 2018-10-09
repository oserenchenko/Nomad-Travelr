## Nomad-Travelr

Nomad-Travelr is a travel wish list/planner for people who want to explore new cities. Users can make an account, search for cities and zoom to them on a global map, save cities as favorites, search for things to do in their saved cities, and save specific venues they want to visit.

______________
______________
______________
## Visit the deployed version of Nomad-Travelr
[Nomad-Travelr](https://oserenchenko.github.io/Nomad-Travelr-Local/)
Checkout the full version of the app with these credentials:
```
email: test@test.com
```
```
password: ChewzyTest1!
```

![homepage]()

______________
______________
______________

## Getting Started
to install locally run this command in your terminal
```
git clone https://github.com/oserenchenko/Chewzy.git
```
once inside the Chewzy folder run 
```
npm install
```

Now we need to make a .env file inside of the main folder and fill in these keys.
These keys can be obtained at [auth0](https://auth0.com) when you register an application.

``` javascript
NODE_ENV="development"
```
``` javascript
AUTH0_CLIENT_SECRET=YOUR_KEY
```
``` javascript
AUTH0_ID=YOUR_ID
```
``` javascript
AUTH0_DOMAIN=YOUR_DOMAIN
```


You will also need to set up a MySql database called chewzy

The last step is to make sure your express sever is running and and type this command in your termial
```
node server.js
```

### Prerequisites

* [Nodejs](https://nodejs.org/)
* [MySql](https://www.mysql.com)


______________
______________
______________
## Built With

* [Expressjs](https://expressjs.com/) - nodejs server side framework
* [MySql](https://www.mysql.com) -open-source relational database management system.
* [Auth0](https://auth0.com) - universal authentication & authorization platform for web, mobile, and legacy applications.
* [Sequelize](http://docs.sequelizejs.com) - romise-based ORM for Node.js v4 and up.

______________
______________
______________
## Authors

* [Olga Serenchenko](https://github.com/oserenchenko)
* [Inna Leikina](https://github.com/innaleikina)

______________
______________
______________
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
