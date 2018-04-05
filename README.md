# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* WeKay UI Theme
* Version 1.0.0
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

#### Install git
[Git Install website](https://git-scm.com/book/fr/v1/D%C3%A9marrage-rapide-Installation-de-Git)

#### Install node
* On Mac
`brew install node`

* On Windows
[Download latest version of node](https://nodejs.org/download/release/latest/)

#### Install Gulp
Semantic UI uses Gulp to provide command line tools for building themed versions of the library with just the components you need.

Gulp is an NPM module and must be installed globally

`npm install -g gulp`

#### Download sources from Wekay-UI repository

`git clone https://github.com/ycorsaire/wekay-ui.git`


#### Install http-server 

http-server is a command-line http server.
[http-server documentation](https://www.npmjs.com/package/http-server)

Installing globally

`npm intall -g http-server`

### Getting started

Open a terminal and launch the following command
`cd wekay-ui`
`npm run build`

The last command will build semantic assets, css and javascript files.

Serve the app with http-server:

`http-server .`

#### Re deploy on file change

For the app to be redeployed on file change, in an other terminal prompt launch the following command

`npm run watch`
