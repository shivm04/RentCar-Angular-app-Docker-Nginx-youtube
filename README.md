![HomePage](https://github.com/Samettkaya/RentA-Car-FrontEnd-Angular/blob/master/Readme-Images/HomePage.PNG)
<br> 

# Docker Commands 
  docker build -t docker-nginx .
  
  docker run -itd -p 9090:80 docker-nginx-container

# Node Verison v16.20.2
  # install commands on ubuntu
    sudo apt-get update
    sudo apt install curl
    sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
    source ~/.bashrc
    nvm list-remote
    nvm install v16.20.2
    nvm use v16.20.2
    npm install -g @angular/cli@11.2.4

# PM2 install 
  sudo npm install -g pm2

# Npm Version 
  8.19.4

# RentACarFrontEnd

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
