
# Portfolio Project

This is a personal portfolio project built with HTML and CSS, following mobile-first and responsive design principles. It includes two main sections for now:

- A navigation toolbar (header)
- A hero (headline) section

This is the first milestone of the full portfolio build.

---

## Project Structure

```
portfolio/
├── pages/                 # Subpages (About, Contact)
├── style/                 # CSS styles
│   └── style.css
├── index.html             # Main landing page
├── .htmlhintrc            # HTMLHint config
├── .stylelintrc.json      # Stylelint config
├── package.json           # Project metadata & scripts
└── README.md
```

---

## How to Run Locally

1. Clone this repo:

   ```bash
   git clone https://github.com/keneanalemayhu/portfolio.git
   cd portfolio
   ```
2. Open `index.html` in your browser to preview the homepage.

---

## Linting

This project uses [Stylelint](https://stylelint.io/) for CSS and [HTMLHint](https://htmlhint.com/) for HTML.

### Run linters:

```bash
# Check HTML files
npm run lint:html

# Check CSS files
npm run lint:css
```

### Auto-fix CSS issues:

```bash
npm run lint:css:fix
```

---

## Pages

- `index.html`: Home page (toolbar and hero section)
- `pages/about.html`: About page (placeholder)
- `pages/contact.html`: Contact page (placeholder)

---

## Design Reference

This project follows a Figma template provided for the course. All fonts, spacing, colors, and layout are designed to match it exactly.

---

## Contributing

This is an individual project, part of a learning program. No contributions are accepted.

---

## 📄 License

This project is licensed for educational purposes.
