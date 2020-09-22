# cypressio-example
Example of using cypress io

![Chrome headless](https://github.com/StephenDavidson/cypressio-example/workflows/Chrome%20headless/badge.svg)

## getting started

Install dependencies

`npm i`

Run the tests

`npm test`


## with docker

`docker run -it --rm -v ${PWD}:/app -w /app cypress/included:5.2.0`

## debugging

`npm run test:dev`
