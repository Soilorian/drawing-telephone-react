# React Drawing Telephone

A browser drawing-and-guessing game prototype with a React/Redux client and an Express server. The local project contains guest and game domains, Sequelize database models, Webpack builds and Cypress fixtures.

## Project layout

- `client/`: React interface, Redux state and browser assets.
- `server/`: Express routes, game/guest domains, middleware and database initialization.
- `cypress/`: supplied browser-test fixtures and support files.
- `webpack.client.js` and `webpack.server.js`: browser and server build configuration.

## Local setup

Install Node.js and npm. Copy `.env.example` to `.env` and adjust it for your machine. From this directory, run `npm ci`, then `npm run run:server`; that script builds the client and server before starting the server. The default address is `http://localhost:3000`.

The dependency versions and build scripts are the supplied legacy versions. Setup, compatibility and gameplay have not been verified by running the application or tests.

## Provenance and scope

Published at the owner's request from the selected local Ubuntu copy, previously named `gartic-phone-main`. Existing source and notices are preserved. The original upstream author and project license have not been established from this copy; this publication makes no claim of sole authorship and assigns no new blanket license. Application source is unchanged. Dependencies, build output, private environment files, runtime databases and redundant archives are excluded.
