# REST API with Node.js, Mongoose & TypeScript

Note: This repository includes the [postman collection for the finished API](postman_collection.json)

Note 2: Make sure you add .env to your .gitignore before pushing any changes to your repository. You mght also want to generate new public & private keys. Mine are disposable


## Issues I encountered and how to fix them
* JWT malformed error: https://youtu.be/FzKrfwplips
* Managing environment variables: https://youtu.be/gfyQzeBlLTI

## What you will need
* A running instance of MongoDB
* Postman (Insomnia/Thunder client/Rapid API client also work)
* An IDE or text editor (I like VS Code so yeah)
* A web browser
* A package manager such as NPM or Yarn
* Node.js installed

## Data flow
![](./diagrams/data-flow.png)


## Access & refresh token flow
![](./diagrams/refresh-token-flow.png)

## Deployment options (I'll probably experiment with all of them lol)
* Docker (image)
* docker-compose (container)
* Caddy - Web server
* DigitalOcean

Note: You will need Docker installed locally if you want to test your Docker configutation

## Let's keep in touch
- [Twitter](https://twitter.com/manuchim_ix)
