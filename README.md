# Abdullah Rahat — Portfolio

A clean, minimalist portfolio website hosted on GitHub Pages.

## Setup

1. Create a new repository on GitHub named `<your-username>.github.io`
2. Push this directory to that repository
3. Go to **Settings → Pages** and set the source to the `main` branch
4. Your site will be live at `https://<your-username>.github.io`

## Adding Your CV

To enable the "Download CV" button:

1. Compile `cv.tex` to PDF using a LaTeX compiler (Overleaf, TeX Live, etc.)
2. Name the output file `Abdullah_Rahat_CV.pdf`
3. Place it in the root of this repository
4. Commit and push

## Structure

```
├── index.html          # Main page
├── style.css           # Styles
├── script.js           # Interactivity
├── cv.tex              # CV source (LaTeX)
├── Abdullah_Rahat_CV.pdf  # CV download (you generate this)
└── README.md
```

## Customization

- **Colors:** Edit the CSS variables in `style.css` (`:root` block)
- **Content:** Edit `index.html` directly
- **Fonts:** Change the Google Fonts import in `index.html`
