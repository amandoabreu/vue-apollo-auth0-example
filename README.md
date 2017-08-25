# vue-apollo-instagram-example
📷  Instagram clone built with Vue 2 &amp; Apollo

## Getting Started

### 1. Create an account

To run this example, please create a [Graphcool](http://graph.cool) account and **copy your endpoint**. This shouldn't take longer than a minute. We promise!

![](http://i.imgur.com/ytXDR4B.gif)

This is how our GraphQL data model looks like:

```graphql
type Post {
  description: String!
  imageUrl: String!
}
```

### 2. Configure app data endpoint

Open `src/main.js` and paste your endpoint to the following line:

```js
const networkInterface = createNetworkInterface({ uri: 'https://api.graph.cool/simple/v1/__PROJECT_ID__' })
```

### 3. Change OIDC Settings

In the auth0 dashboard, go to Client > Advanced Settings > OAuth
and set the OIDC Conformant flag to false.

![](http://i.imgur.com/eZCf1c6.png)

### 4. Run the example

You're done configuring the example application. Please run the following command and open [localhost:3000](http://localhost:3000) in your browser. Have fun exploring! 🎉

```sh
yarn && yarn start
# or npm install & npm start
```


## Help & Community [![Slack Status](https://slack.graph.cool/badge.svg)](https://slack.graph.cool)

Join our [Slack community](http://slack.graph.cool/) if you run into issues or have questions. We love talking to you!

![](http://i.imgur.com/5RHR6Ku.png)
