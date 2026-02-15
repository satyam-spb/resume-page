# Resume Page

A clean, single-page HTML resume for Piyush Choudhary — Full Stack Developer.

## Setup

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd resume-page
   ```

2. **No build tools or dependencies required.** This is a pure HTML page with inline styles.

## Usage

### Open directly in a browser

Double-click `resume.html` or run:

```bash
open resume.html        # macOS
xdg-open resume.html    # Linux
start resume.html       # Windows
```

### Serve with a local development server (optional)

Using Python:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/resume.html`.

Using Node.js (npx):

```bash
npx serve .
```

## Customisation

Edit `resume.html` directly to update:

- **Personal info** — name, tagline, and about section in the `<header>` and first `<section>`.
- **Skills** — add or remove `<li>` items in the Skills section.
- **Experience / Education** — add or remove `<tr>` rows in the respective tables.
- **Projects** — add new `<article>` blocks inside the Projects section.
- **Contact** — update email, phone, and location in the `<footer>`.
- **Styling** — modify the `<style>` block in `<head>` or link an external CSS file.

## License

&copy; piyushsirkivalentine. All rights reserved.
