# Minjin Kim — Quarto website

Preview locally from this folder:

```bash
quarto preview
```

## Add a portrait
1. Create an `images` folder.
2. Put your photo there as `portrait.jpg`.
3. In `index.qmd`, replace:

```html
<div class="portrait-note">portrait.jpg</div>
```

with:

```html
<img src="images/portrait.jpg" alt="Minjin Kim">
```

Edit page text in the `.qmd` files. Edit the visual design in `styles.css`.
