# Madeline Fisher — Portfolio

A personal portfolio website for Madeline Fisher, designer and visual artist.

## Structure

```
index.html      Page markup (Hero, About, Work, Experience, Awards, Contact)
styles.css      Styling — warm cream / sage / charcoal palette
script.js       Nav, mobile menu, and scroll-reveal interactions
assets/         Images (add your portrait here as madeline.jpg)
```

## Add your photo

Drop your portrait into `assets/` named **`madeline.jpg`**:

```
assets/madeline.jpg
```

Until that file exists, the hero shows a styled "MF" monogram fallback
automatically — so the site always looks finished.

## View locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

1. Push this branch and merge to `main`.
2. In the repo's **Settings → Pages**, set the source to the `main` branch.
3. Your site will be live at `https://<username>.github.io/maddiefisher/`.

## Customize

- **Work cards** live in the `#work` section of `index.html`. Swap the
  colored `.card__media` placeholders for real project images when ready.
- **Instagram link** in the Work section — replace `https://instagram.com`
  with your profile URL.
- Colors are CSS variables at the top of `styles.css` (`:root`).
