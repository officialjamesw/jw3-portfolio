# James Wilson III — Portfolio

Terminal UI portfolio site. Single-page, no build step required.

## Deploy

### Netlify (recommended)
1. Drag the entire folder into https://app.netlify.com/drop
2. Or: connect your GitHub repo and set publish directory to `/`

### GitHub Pages
1. Push this folder to a repo (e.g. `jw3-portfolio`)
2. Go to Settings → Pages → set source to `main` branch, root `/`
3. Your site will be at `https://<username>.github.io/jw3-portfolio/`

### Vercel
1. `npm i -g vercel && vercel` from this directory
2. No framework preset needed — static site

## Structure
```
index.html          ← main site (Terminal UI)
assets/
  japan-arashiyama.png
  subway-comiccon.png
papers/
  Adversarial_Face_Recognition__Detection_Framework_for_Video_Based_Attack_Sequences.pdf
  Detecting_AI_Generated_Phishing_Through_Sender_Style_Communication_Drift.pdf
  Technology_Review_Secure_AI_Paper.pdf
_redirects          ← Netlify SPA redirect rule
netlify.toml        ← Netlify config + security headers
```
