# KCC ITM Student Registration System


A modern, responsive, and fully interactive Student Registration Web Application built using HTML, CSS, and JavaScript. This project provides a premium UI/UX experience with real-time validation, password strength checking, and local storage data handling.

🚀 Features

✨ Modern UI Design

Dark themed premium interface

Smooth animations & transitions

Responsive layout (mobile + desktop)

🧠 Smart Form Validation

Real-time input validation

Name, Email, Phone, DOB checks

Error & success indicators

🔐 Password Security

Password strength meter

Requirements checker (uppercase, number, symbol, etc.)

Show/Hide password toggle

📊 Progress Tracking

Live form completion percentage

Interactive progress bar

💾 Local Storage Integration

Saves submitted data in browser

Displays recent registrations

Option to clear saved data

✅ User Experience Enhancements

Success confirmation screen

Auto-scroll to errors

Animated feedback

- Real-time analysis

- Enhanced user experience

## Security notes

- Passwords are validated in the browser but are **never stored**.
- Saved registrations stay in this browser only (localStorage, newest 50) and all saved text is escaped before display.
- This is a front-end project: connect the submit handler to a backend to store registrations on a server.

## Run locally

Open `index.html` in any modern browser. No install or build step is needed. To serve it over HTTP instead:

```bash
python3 -m http.server 8000
```

## Deploy

This repository includes a GitHub Pages workflow (`.github/workflows/pages.yml`).

1. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
2. Push to the default branch. The site is published at `https://<username>.github.io/registration-form-with-real-time-validation/`.

Any static host (Netlify, Vercel, Cloudflare Pages) also works: publish the repository root with no build command.
