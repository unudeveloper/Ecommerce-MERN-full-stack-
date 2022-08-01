# BuyStop-Project.
This project is shopping websites.
There you can buy anything you want.
One shop for all your digital needs.

A project made using MongoDB ,Express.JS, Node.JS, and React.
## Quick Install
Once you've cloned the repo and installed all the prerequisites, you're just a few steps away from interfacing with the neo blockchain and building your application.

The boilerplate comes pre-bundled with a `package.json` and `bower.json` files that contain the list of modules you need to start your application.

To install the dependencies, run this in the application folder from the command-line:

```bash
$ npm install
```

This command does a few things:
* First it will install the dependencies needed for the application to run.
* If you're running in a development environment, it will then also install development dependencies needed for testing and running your application.
* When the npm packages install process is over, npm will initiate a bower install command to install all the front-end modules needed for the application
* To update these packages later on, just run `npm update`

## Running Your Application

Run your application using npm:

```bash
$ npm start
```

Your application should run on port 3000 with the *development* environment configuration, so in your browser just go to [http://localhost:3000](http://localhost:3000)

That's it! Your application should be running. To proceed with your development, check the other sections in this documentation.
If you encounter any problems, try the Troubleshooting section.

Explore `config/env/development.js` for development environment configuration options.

*Note: development mode will sync to the testnet and production mode will sync to mainnet.  Parallel syncronization is not currently supported.  
### Functionalities Implmented:

1. User's can login using JSON Web Token.
2. New users can register themselves.
3. Products can be added to cart.
4. Quantity of Products can be changed after adding them to cart.

### Being-Implemented
5. User can add comments, reviews to various purchased products.
6. An Admin display for the admin to add new products to the site.
7. A payment portal for users to pay for there products.
8. A status site where user can see the status of there order which has been placed

![screencapture-localhost-3000-2021-02-26-22_54_40](https://user-images.githubusercontent.com/67420435/109335624-50b72f80-7888-11eb-92f9-3aaff43a0146.png)
