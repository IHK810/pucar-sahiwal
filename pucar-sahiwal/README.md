# PUCAR Sahiwal Website

Website for **Punjab Council of the Arts, Sahiwal (PUCAR)**.

## Project structure

```text
pucar-sahiwal/
├── index.html
├── style.css
├── script.js
└── assets/
    ├── images/
    │   ├── hero.jpg
    │   ├── majeed-amjad.jpg
    │   ├── gallery-1.jpg
    │   ├── gallery-2.jpg
    │   ├── gallery-3.jpg
    │   └── gallery-4.jpg
    └── books/
        ├── book-1.pdf
        ├── book-2.pdf
        └── book-3.pdf
```

## Add your own photos

Put your images in `assets/images/` using the filenames used in `index.html`, or edit the filenames in the HTML.

Recommended:
- `hero.jpg`: wide landscape photo, at least 1800px wide
- `majeed-amjad.jpg`: portrait
- `gallery-1.jpg` to `gallery-4.jpg`: event/exhibition photographs

## Add Majeed Amjad books

Put permitted PDF files in `assets/books/` and rename them:
- `book-1.pdf`
- `book-2.pdf`
- `book-3.pdf`

Then edit the book titles in `index.html`.

**Copyright:** only publish PDFs for which PUCAR has permission to distribute them, or material that is legally in the public domain.

## Deploy on GitHub + Vercel

1. Create a new GitHub repository, e.g. `pucar-sahiwal`.
2. Upload all files and folders from this project.
3. Go to Vercel and sign in with GitHub.
4. Choose **Add New → Project**.
5. Import the `pucar-sahiwal` GitHub repository.
6. Framework preset: **Other** (or leave it detected as a static site).
7. Build command: leave empty.
8. Output directory: leave empty.
9. Click **Deploy**.

Every future push to the GitHub `main` branch will trigger a new Vercel deployment.

## Custom domain

After deployment, in Vercel open:
**Project → Settings → Domains**

Add the council's domain and follow Vercel's DNS instructions.
