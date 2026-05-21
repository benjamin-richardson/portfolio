# Portfolio

A single-page personal site. The whole site is `index.html`.

## Deploy to Railway

1. Push this folder to a new GitHub repo.
2. On [railway.com](https://railway.com): **New Project → Deploy from GitHub repo** → pick the repo.
3. Railway auto-detects `package.json`, runs `npm install`, then `npm start`.
4. Under the service's **Settings → Networking**, click **Generate Domain** to get a public URL.

`npm start` serves the static files with [`serve`](https://www.npmjs.com/package/serve) on the port Railway provides via `$PORT`.

## Run locally

```sh
npm install
npm start
```

Then open http://localhost:3000
