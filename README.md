# Device-Gateway-Manager

## Description

This project is a REST-API for managing gateways (master devices that control multiple peripheral devices). Implemented using express.js and mongoose.js

## Testing the app

```bash
# all the tests
$ yarn test 

# specific ones
$ yarn test name-of-the-test
```

## Postman test use

See the postman use [here](/api-colection/README.md).

## Running the app

```bash
# development | prod
$ yarn start
```

## Running the app and Swagger

```bash
# generate the docs and start the app
$ yarn swagger-generate
```

explore at <http://localhost:3000/api-docs>

## MongoDB setup

There is no difference on whether to use mongo locally or in a docker container, for both cases the mongo service must be running.
