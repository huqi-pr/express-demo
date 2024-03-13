# Express Demo

- Use [Express](http://expressjs.com/) 5.x.
- Use [Vercel](https://vercel.com/).

# Key Configuration

- vercel.json
```json
{
    "builds": [{ "src": "app.js", "use": "@now/node" }],
    "routes": [{ "src": "(.*)", "dest": "app.js" }]
}
```