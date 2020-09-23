# ice-spa-app

> This Single Page App (SPA) makes Ice customers happy.

Important:

> This application is provided “AS IS” with no express or implied warranty for accuracy or accessibility. The sample code is intended to demonstrate how Okta can integrate with custom applications and does not represent, by any means, the recommended approach or is intended to be used in development or productions environments.

## Run this App

### Option 1: Heroku

1. Click [![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
2. Login or create your Heroku account.
3. After deployment, go to settings.
4. Update each property with an appropriate value.

### Option 2: In my house

1. Install `git` and `node` in your computer.
2. Clone this repo:
3. Install Node dependencies:
    `npm install`
3.2 `npm install @okta/okta-auth-js@2.6.0 --save`
3.5 create env variables for:
    PORT=8081
    OKTA_SUBDOMAIN={your-okta-tenant}
    OKTA_CLIENT_ID={SPA app client ID}
4. Run the Project:
    `npm run dev`

### To build a production version

1. To build for production with minification
    `npm run build`

2. To build for production and view the bundle analyzer report
    `npm run build --report`
