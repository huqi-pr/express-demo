# Express Demo

- Use [Express](http://expressjs.com/) 5.x.
- Use [Vercel](https://vercel.com/).

## Key Configuration

- vercel.json
```json
{
    "builds": [{ "src": "app.js", "use": "@now/node" }],
    "routes": [{ "src": "(.*)", "dest": "app.js" }]
}
```

## How to create

- Create a new project by [express-generator](https://github.com/expressjs/generator) then run it.

```bash
# available in Node.js 8.2.0
npx express-generator --view=pug myapp
cd myapp

# run
npm install && npm start
```

- Add `vercel.json` then deploy by [vercel](https://github.com/vercel/vercel).

```bash
# add vercel.json and deploy
npx vercel login
npx verce
```
