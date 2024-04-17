# sctp-first-node-application

- run API
```
node index.js
```

- containerize node app
```
docker build -t sctp-node . 
docker run -dp 7777:3000 sctp-node
```