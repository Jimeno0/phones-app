# Phones App

## Prerequisites
* You need to have installed [docker](https://www.docker.com/get-started) and [docker-compose](https://docs.docker.com/compose/install/)
## Use

* For production use run:
    ```bash
      docker-compose -f docker-compose.prod.yml up --build
    ```
    then visit [http://localhost:3000](http://localhost:3000)

* For development use run:
    ```bash
      docker-compose up --build
    ```
    then visit [http://localhost:3000](http://localhost:3000)


## Tests

### Unit tests
* Go inside the font app `cd phones-frontend`
* Run `yarn` or `npm install` to install the depencencies
* Run `yarn test` or `npm run test` to start the unit tests

### End to end tests
Note:  you need the app up and running so run one of the previous **Use commands**.

I.E: `docker-compose -f docker-compose.prod.yml up --build`
* Go inside the font app `cd phones-frontend`
* Run `yarn` or `npm install` to install the depencencies
* Run `yarn e2e` or `npm run e2e` to start the end to end tests

## Notes

I started to develop both frontend and backend project as separated repos. In case you want to track the projects progression you can check the legacy repos [phones-frontend](https://github.com/Jimeno0/phones-webapp) and [phones-backend](https://github.com/Jimeno0/phones-backend).

I deceided to merge both in one project when I started to work with docker :)


