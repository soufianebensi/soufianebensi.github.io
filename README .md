# Soufiane Kamal Benslimane: personal website

Static site, no build step. Files:

- `index.html`: the whole site
- `soufiane.jpg`: your portrait (must sit next to index.html)
- `robots.txt`: lets search engines crawl it

## Before publishing: fill in your details

Open `index.html` and search for `hidden`:

1. Email and LinkedIn are already filled in
2. **CV button**: put your PDF in this folder named `Soufiane-Kamal-Benslimane-CV.pdf`, then delete `hidden` on `id="cv-btn"`

## Publish free on GitHub Pages (no domain needed)

1. Create a GitHub account, then a new **public** repository named `YOUR-USERNAME.github.io`
2. Upload `index.html`, `soufiane.jpg`, `robots.txt` (and your CV PDF if you have one)
3. Repository → Settings → Pages → Source: *Deploy from a branch* → `main` / root
4. After a minute the site is live at `https://YOUR-USERNAME.github.io`

Netlify Drop (app.netlify.com/drop) is an alternative: drag the folder in and get a free link.

## Make it findable on Google

1. Add this inside `<head>` with your real URL: `<link rel="canonical" href="https://YOUR-USERNAME.github.io/">`
2. Open Google Search Console → add your URL → *URL Inspection* → *Request indexing*
3. Put the site link in your LinkedIn profile and CV, because links from other pages help ranking
4. Searching your full name can take days to weeks to show the site; this is normal
