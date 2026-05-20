# Publish OM SUPATHAM HOSPITAL Website

This website is a static HTML/CSS/JavaScript site. It can be published on GitHub Pages, Netlify, Vercel, or any normal web hosting.

## Files to publish

Upload everything in this folder:

- `index.html`
- `patient.html`
- `appointment.html`
- `gallery.html`
- `contact.html`
- `admin.html`
- `server.js` is only for local preview and is not needed by most static hosts.
- `assets/`
- `.nojekyll`

## Local preview

Run:

```bash
node server.js
```

Then open:

```text
http://127.0.0.1:8080
```

## Important note

This is currently a front-end static demo. Admin settings, appointments, uploaded images, and password changes are saved in the visitor browser using local storage. For a real hospital production website, add a backend database, secure authentication, and an SMS gateway.
