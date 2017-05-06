# Bookmark Server
The [Live Version](https://short-bookmark.herokuapp.com) of this app is hosted on Heroku.

## About:
It is a *bookmark server* or URL-shortening service,
similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.

