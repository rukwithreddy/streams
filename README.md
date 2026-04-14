# stream_node

A simple Express.js server that reads `sample.txt` and serves it on the root route.

## Prerequisites

- Node.js 18+ (recommended)
- npm

## Install

```bash
npm install
```

## Run

```bash
npm start
```

Server starts at:

- http://localhost:8000

## Development Mode

```bash
npm run dev
```

## Project Structure

- `index.js` - Express server entry point
- `sample.txt` - Sample file content served at `/`
- `package.json` - Scripts and dependencies

## Available Route

- `GET /` - Returns contents of `sample.txt`

## Notes

- This is a Node.js project. `requirements.txt` is included only for environments that expect it.
