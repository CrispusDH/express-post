- start server: `npm start`

- for sending post with data you could use `curl`:
`curl -d '{"key1":"value1", "key2":"value2"}' -H "Content-Type: application/json" -X POST http://localhost:3000/data`

you will get `{ key1: 'value1', key2: 'value2' }`

