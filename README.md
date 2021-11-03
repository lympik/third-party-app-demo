# Third Party App Demo

Lympik authentication server is compliant with OpenID Connect Dynamic Client Registration specification.
To get started please register your application like described here:
https://auth0.com/docs/configure/applications/dynamic-client-registration#use-dynamic-client-registration.
Use the generated `client_id` in this application. Your `redirect_uri` can also use localhost for testing purpose.

## Installation
Run `npm install` to install the required dependencies. Insert your `client_id` in `index.html`.´

## Run

Run `npm start` to run the development server. You can login and get an access token. This access token is used to access the Lympik API.
You can use different flows depending on your application (https://auth0.com/docs/authorization/flows) 

### Disclaimer

This is no production ready software.
