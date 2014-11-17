  #realtime
=================

[http://noded3.herokuapp.com](http://noded3.herokuapp.com)

Based on your desired hashtag, view live Instagram posts around the world beautifully in realtime.

We wanted to mainly experiment witth D3.js, as well as build a Node.js application from scratch. Also utilizes websockets to provide live updates to the client from the server.

###To run locally:

1. Install package dependencies: `$ npm install`
2. Using `config/default.sample.json` as an example, create a `config/default.json`
  - Fill in your Instagram client ID and client secret
  - Using a tunnel such as [ngrok](https://ngrok.com/), put your url in `"root_url"` to direct your Instagram subscriptions
3. Run! `$ npm start`
4. To run tests: `$ npm test`
