# Taeseong Yoon — Personal Academic Website

This is a static GitHub Pages website.

## File structure

```text
YOUR_GITHUB_ID.github.io/
├── index.html
├── style.css
└── assets/
    └── profile.jpg
```

## Add or replace the profile photo

1. Create an `assets` folder in the same directory as `index.html`.
2. Put the profile image in that folder and name it exactly `profile.jpg`.
3. Commit and push the file together with `index.html` and `style.css`.

The page already loads the image from this CSS rule:

```css
background-image: url("assets/profile.jpg");
```

A square image is recommended. A portrait around `800 × 800 px` or larger works well. The CSS crops it into a circle with `background-size: cover`. To move the visible crop upward or downward, edit this line in `style.css`:

```css
background-position: center 28%;
```

Examples:

```css
background-position: center center; /* centered */
background-position: center 20%;    /* show more of the upper part */
background-position: center 40%;    /* show more of the lower part */
```

Until `assets/profile.jpg` is added, the circular `TY` fallback remains visible instead of showing a broken image.

## Publish with GitHub Pages

1. Create a GitHub repository named `YOUR_GITHUB_ID.github.io`.
2. Upload `index.html`, `style.css`, and the `assets` folder to the repository root.
3. Commit and push.
4. Open `https://YOUR_GITHUB_ID.github.io`.

## Notes

- Replace remaining `#` placeholders for paper code or BibTeX links when those URLs are available.
- The CV button currently points to the existing Overleaf read-only URL.
