# Game Database (Backend)

This is a Node.js Express based backend with the sole purpose of acting as a proxy between our Frontend and the RAWG API. Sign up to get a key [here](https://rawg.io/apidocs).

This allows us to safely call the API without leaking our API key in the Frontend.

# How to Run Locally

Assuming you have Node and NPM already installed.

- Create an .env file with the following content.

```
API_KEY=<Replace with your API key>
CLIENT_DOMAIN=<Replace with the client's domain for example : http://localhost:5173>
PORT=3000
```

- Run `npm install`
- Run `node index.js`
- Clone and run the Frontend. You can find it [here](https://github.com/JSLegendDev/Game-Database-Frontend).
