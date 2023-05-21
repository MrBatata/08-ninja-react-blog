# JSON Server > Building a full fake REST API

https://github.com/typicode/json-server
1- `npm i json-server`

2- Create data/db.json: this will be your fake db server

3- Terminal in data/: `npx json-server --watch db.json --port 8000`
We can create json-server.json with config, so no need to add -port 8000...
`{"port": 8000}`
