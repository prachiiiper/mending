# Mending

A short, gentle pixel game for a broken heart. A small cracked heart walks through six quiet scenes, finds small kind things, and each one mends part of the crack with gold (kintsugi). There's no way to lose.

Made by [byteyourweb](https://byteyourweb.com).

## Run locally

It's one static file. Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Controls

- ← → or A / D: walk
- Space or E: look closer, continue text
- On phones: on-screen buttons

## Deploy (Vercel)

```
vercel            # first run links the project, gives a preview URL
vercel --prod     # production
```

Custom domain: in the Vercel dashboard, Project → Settings → Domains → add `mending.byteyourweb.com`, then add the CNAME record it shows (`cname.vercel-dns.com`) at your DNS provider.
