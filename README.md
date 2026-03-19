# ray-meets-world

A tiny static website that renders **Hello World!**.

## Run locally

You can open `index.html` directly in your browser, or serve it with Python:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy on Vercel (recommended)

1. Push this repository to GitHub.
2. Go to <https://vercel.com/new> and import the repo.
3. Framework preset: **Other** (or **Static Site** if shown).
4. Leave build settings empty and deploy.

Vercel will give you a live URL instantly and redeploy on every push to `main`.
