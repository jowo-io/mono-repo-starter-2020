# Server

Uses a custom webpack config to generate a single bundle file which can be deployed to a remote server. Is configured with Jest, ES6/Babel, Express. It is run in the background with Nodemon which has been configured with Node/Chrome `--inspect` for much easier debugging.

# Getting started

To develop, run:

`npm run dev`

> NOTE - console logging output in the terminal/command prompt is disabled by the webpack config. Node --inspect has been enabled instead!

To run tests either follow the guide in the [main README](/README.md) or run:

To open the server's console open the chrome browser’s console and you’ll see a little green icon once the server npm run dev script has been started.

<img src="https://www.jowo.io/posts/javascript-dev-stack-2020/node-inspect-chrome-developer-console.png" alt="node --inspect mode" />

Click it and a headless console will open which is connected to server's Node script!

<img src="https://www.jowo.io/posts/javascript-dev-stack-2020/node-inspect-hello-world.png" alt="headless chrome console for node deugging" />

`npm run jest`

To build the server simply run:

`npm run build`

The server bundle is output to `build/server.bundle.js`.
