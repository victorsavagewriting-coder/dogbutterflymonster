# Becoming Chimeric — Workshop WebAR

A simple WebAR viewer for the **Becoming Chimeric** workshop. Each participant creates their own copy of this template, drops in their chimera `.glb`, and publishes a stable GitHub Pages URL for phone AR.

Built with [Google `<model-viewer>`](https://modelviewer.dev/) (WebXR / Scene Viewer / Quick Look).

## Use this template

1. On GitHub, open this repository and click **Use this template** → **Create a new repository**.
2. Name it something clear (e.g. `my-chimera-webar`) under your own account.
3. Keep the repo **public** so GitHub Pages can host it for free.

Do **not** fork unless you specifically need fork workflows — a template copy is cleaner for workshop use.

## Add your model

1. Replace `assets/cube.glb` with your own `.glb` (same filename), **or**
2. Put your file in `assets/` and update the `src` on `<model-viewer>` in `index.html`.

Optional USDZ for iOS Quick Look can be added with `ios-src` on `<model-viewer>` if you have one.

## Personalize the page

| File | What to change |
| --- | --- |
| `index.html` | `<title>`, `chimera-name` text, model `src` |
| `about.md` | About overlay text (Markdown) |
| `my-styles.css` | Colors / layout only if needed |

Keep the AR button and `<model-viewer>` attributes intact so AR keeps working.

## Enable GitHub Pages

1. In your new repo: **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)` → **Save**.
4. After a minute or two, your site is live at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME/
```

Example (this template repo, once Pages is on):

```text
https://martinamenegon.github.io/becoming-chimeric-workshop-webar/
```

Open that URL on a phone for AR, or on desktop use the **AR** button to show a QR code.

## Workshop tip

Share your Pages URL with the group during Manifesting so others can view your chimera in AR without installing an app.
