# Notes API

A small REST API for notes, built for the StepCode **Basic Notes API** project.
Express on Node.js, with an in-memory store.

The contract is in [`openapi.yaml`](openapi.yaml).

## Run it locally

You need Node.js 20 or newer.

```bash
npm install
npm start        # http://localhost:3000
```

Check it's up:

```bash
curl http://localhost:3000/health
# {"status":"ok"}
```

Set `PORT` to use another port.
