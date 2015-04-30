## A RESTful API using NodeJS, MongoDB and Express-Stormpath

This application is a simple "TODO" list API. Users interact with the API using API key/id pairs. Users sign up using a simple process via the Stormpath API. The Express-Stormpath NPM module handles all of the user sign-in, registration and authentication processes, alleviating the user of the responsibilities of creating, storing and authenticating users.

In order to use Stormpath, you must [sign up](https://stormpath.com/) to use their API. This will give you an API Key file. Use this in the application, or use environment variables to pass in the id/secret (as I have done in stormpath.init).
