# How to Use
In order for this to work, you need a petfinder API and secret key which you can get from their [API docs](https://www.petfinder.com/developers/v2/docs/)

Once you have those, create a javascript file called `api-keys.js` in the root project directory which exports the petfinder API key as `petFinderKey` and exports the secret key as `petFinderSecret`. This file is included in the .gitignore file, to avoid exposing those keys to the public.
