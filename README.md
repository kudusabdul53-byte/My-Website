# Abdul Kudus — Portfolio (My-Website)

A simple, responsive portfolio website built with plain HTML, Tailwind CSS (via CDN), and a few small JavaScript helpers for mobile navigation and scroll animations.

This repository contains a single-page portfolio `index.html` intended as a starter or personal portfolio template.

## What’s included

- `index.html` — the full website (header, home, about, projects, contact, footer).
- `README.md` — this file.

## Built with

- HTML5
- Tailwind CSS (via CDN)
- Small vanilla JavaScript (no frameworks or build step)
- Google Fonts (Inter)

## Quick preview (no install)

The site is static — you can open it directly in your browser by double-clicking `index.html` or using PowerShell:

```powershell
# Open the file in your default browser from PowerShell (from project folder)
Start-Process .\index.html
```

If you prefer serving the files over a local HTTP server (recommended for testing assets), run one of these from the `My-Website` folder.

Using Python 3 (works on Windows if Python is installed):

```powershell
# Start a simple HTTP server on port 8000
python -m http.server 8000
# then open http://localhost:8000 in your browser
Start-Process "http://localhost:8000"
```

Using Node (http-server) if you have Node.js installed:

```powershell
# install once (global)
npm install -g http-server
# run from project folder
http-server -p 8000
Start-Process "http://localhost:8000"
```

## How to customize

- Edit the page title, name, and copy in `index.html`.
- Replace the placeholder image with your own photo (image tag in the Home section).
- Modify the tailwind classes directly in the markup — this template uses the Tailwind CDN, so no compilation is required.
- If you want to switch to a Tailwind build step (recommended for production to purge unused CSS), create a node project and follow Tailwind's official install guide.

## Notes & Considerations

- Tailwind is included via CDN in `index.html` for convenience. For production use, consider installing Tailwind locally and purging unused CSS to reduce file size.
- The mobile menu toggles a `hidden` class; JavaScript is inlined at the bottom of `index.html`.
- The design uses external fonts (Google Fonts). If you need full offline support, download the font files and host them locally.

## Contributing

Small tweaks and improvements welcome. For a personal site, typical next steps are:

- Replace placeholder content and images.
- Add analytics or contact form handling.
- Add a small build step for Tailwind so you can use custom config and remove unused CSS.

## License

This project currently has no license configured. If you want to publish or share it, add a `LICENSE` file (for example MIT or Apache-2.0).

## Contact

If this is your portfolio, update the contact/email details in `index.html`.

---

Requirements coverage:
- Add a README file to the project — Done (`README.md` created at project root).

If you want, I can also:
- Add a basic `LICENSE` file (MIT) and/or a `package.json` with a small "preview" script.
- Convert Tailwind CDN usage to a dev/build setup (PostCSS + Tailwind) if you'd like a production-ready workflow.

Tell me which of those (if any) you'd like next.