# Phones App

## Prerequisites
* You need to have installed [docker](https://www.docker.com/get-started) and [docker-compose](https://docs.docker.com/compose/install/)
## Use

* For production use run:
    ```bash
      docker-compose -f docker-compose.prod.yml up --build
    ```

* For development use run:
    ```bash
      docker-compose up --build
    ```

## Tests

### Unit tests
* Go inside the font app `cd phones-frontend`
* Run `yarn test` to start the unit tests

### End to end tests
Note:  you need the app up and running so run one of the previous **Use commands**.

I.E: `docker-compose -f docker-compose.prod.yml up --build`
* Go inside the font app `cd phones-frontend`
* Run `yarn e2e` to start the end to end tests


