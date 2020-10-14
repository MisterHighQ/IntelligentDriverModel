# IntelligentDriverModel

#### A simple implementation of the Intelligent Driver Model differential equations for simulating traffic flow.

## Setup

To use the application, first navigate to `src/helpers/write_db.js` and configure the template database file as required (e.g. by changing vehicle parameters and adding latent behaviours). Use a NodeJS terminal to execute this script. This will produce a corresponding JSON database file in `src/helpers/db`.

Once the database is created, navigate to the root directory and:
- If you wish to visualise the simulation in a browser, compile the `src/app.js` file using a module bundler such as WebPack.
- If you wish to store the data in a file, execute `src/app.js` in a NodeJS terminal.
