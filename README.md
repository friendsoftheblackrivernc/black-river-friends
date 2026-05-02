# Friends of the Black River NC — Static Website

A clean, fully static HTML/CSS/JS website mirroring the content of [blackriverfriends.org](https://blackriverfriends.org), built for easy hosting on GitHub Pages or any static host.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Home page with hero, mission, stats, goals, and board |
| `about.html` | Ecological significance, conservation goals, historical attributes |
| `news.html` | Latest news and endorsement document downloads |
| `learn.html` | Curated websites, articles, and books about the river |
| `gallery.html` | Photo gallery and Google Maps embed |
| `contact.html` | Contact form and mailing address |
| `css/style.css` | Shared stylesheet (Google Fonts, CSS variables, responsive layout) |
| `js/main.js` | Mobile nav toggle and active-link highlighting |

## Hosting on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`.
4. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Live Form Submissions

The contact form is purely static. To enable real email delivery, replace the `handleSubmit` function in `contact.html` with one of:

- **[Formspree](https://formspree.io/)** — free tier, no backend needed
- **[Netlify Forms](https://www.netlify.com/products/forms/)** — if hosting on Netlify
- **[EmailJS](https://www.emailjs.com/)** — client-side email sending

## Credits

- Content: [Friends of the Black River NC](https://blackriverfriends.org)
- Photography: Mac Stone, Dan Griffin, Alan Clark
- Fiscal Sponsor: [Southern Conservation Partners](https://www.conservationsouth.org/)
