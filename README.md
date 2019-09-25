# Svelte.js + Flask

A super simple example of using Flask to serve a Svelte app and use it as a backend server.

Run the following for development:

- `python server.py` to start the Flask server.
- `cd client; npm install; npm run autobuild` to automatically build and reload the Svelte frontend when it's changed.

This example just queries the Flask server for a random number.
