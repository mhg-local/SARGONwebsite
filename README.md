# SARGON-website

This is a website for [SARGON](https://).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation

```sh
git clone https://git-ce.rwth-aachen.de/acs/private/research/n5geh/all/sargon-website.git
```
```sh
cd sargon-website
npm install
npm run develop
```
This will start a local development server. The server will start at http://localhost:8080/ with hot-reloading etc.

### Deployment

```sh
cd sargon-website
npm run build
```
This will generate static files in the `./dist` directory which can be hosted anywhere, even on a CDN. There is no need for a Node.js server.
 
## Built With
 
 * [Vue.js](https://vuejs.org/) - The javascript framework
 * [Gridsome](https://gridsome.org/) - The Vue.js framework
 * [gridsome-portfolio-starter](https://github.com/drehimself/gridsome-portfolio-starter) - Theme for Gridsome

