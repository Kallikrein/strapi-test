# strapi-test

## initialisation

The strapi depends on binary modules, it's recommended to install via the same OS as the runtime

`docker run --rm -it -v $PWD/server:/src -w /src node npm i`

## launch

`DB_USER=ANYUSER DB_PASSWORD=ANYPASSWORD docker-compose up`

open http://localhost:1337

## issue

When creating a new user I can't log with it, or recovering password with the provided email fails: email not found.
