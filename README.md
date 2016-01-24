Clarifai JavaScript Starter
===========================

This is a basic starter project for using the [Clarifai API](http://clarifai.com).

## Usage

To get started, create an account at [developer.clarifai.com](http://developer.clarifai.com).

Create an application, and get your Client ID and Client Secret.

This basic starter uses your Client ID and Client Secret to get an access token.
Since this expires every so often, the client is setup to renew the token for
you automatically using your credentials so you don't have to worry about it.

You'll notice that in the `.gitignore` file, it references a `keys.js` file. 
This is for security purposes, so you don't share your Client ID and Client
Secret with others.  Create a `keys.js` file and have it look like the following:

```
var CLIENT_ID = 'your ID here';
var CLIENT_SECRET = 'your secret here';
```

Then you're all set! Happy Clarifai-ing. :)
