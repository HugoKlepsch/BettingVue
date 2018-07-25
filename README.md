# BettingVue

BettingVue is a site that allows a number of users to place hidden bets, 
then reveal them after a set amount of time. 

Ex:

- Hugo, Dan, Travis, Chris and Ray all want to place a bet without letting
each other know what their bets are.
- The bets should be in by noon
- At noon the bets will be revealed to all players
- Eventually the bet will be resolved and the winner decided

Requirements for MVP
- Users can "log in" and protect their account with a password
- Users can create a betting session which determines time of bets revealing
- Users can place bets into a session
- Users can view bets placed in a session once the session timer expires

Stretch goals
- Okta SSO integration 
- Pretty Vue.js UI

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
