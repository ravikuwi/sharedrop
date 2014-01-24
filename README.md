FileDrop
========

It uses PeerJS server at http://file-drop-peer-server.herokuapp.com.

## Setup
1. Run `npm install` to install dependencies.
2. Install [foreman](https://github.com/ddollar/foreman) using `gem install foreman`, unless you already have it installed.
3. Create `.env` file and set the following environment variables there:

    ```
    HOST=localhost
    PORT=8000
    WEB_PORT=8000
    SECRET=some-random-string
    ```

4. Run `foreman start` to start the server on `localhost:8000`.