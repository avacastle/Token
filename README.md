[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

facebook-access-token Node.js Express Server for grabbing Facebook Access Tokens
================================

`facebook-access-token` is an Express app that fetches Facebook Access Tokens for any specified app without having to spin up a server. Useful for adding tokens to IoT devices and anywhere else you don't have user interaction with a web browser.

** User tokens that are fetched are long-lived access tokens **

** App access tokens will need to be url encoded prior to being sent to most request libraries (there is a vertical bar `|` in the access token) **

## Installation

Deploy with heroku using the provided heroku deploy button

#### or

```
npm install
foreman start
```

Then navigate to localhost:5000

## How to use

* Enter Facebook App Id and Secret into the form fields
* If you want a user access token with special permissions, enter the permissions comma separated without spaces
* Hit the appropriate button to fetch your user access token or your app access token

** Make sure you have your domain added to the valid callback domains in your Facebook App Settings **
