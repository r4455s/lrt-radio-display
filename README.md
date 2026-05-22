# LRT Radio for Meta Ray-Ban Display

A minimal HTTPS-hostable Web App for Meta Ray-Ban Display glasses. It plays LRT Radijas live audio using the direct HLS stream.

## Files

- `index.html` — complete standalone web app.

## Run locally

```bash
python3 -m http.server 8080
```

Open: `http://localhost:8080`

## Deploy

Deploy the folder to any HTTPS static host, for example Netlify, Vercel, GitHub Pages, Cloudflare Pages, or your own server. Then open the HTTPS URL from the Meta Web Apps flow.

## Notes

Browsers generally require a user gesture before playing audio, so the app starts after pressing Play.
