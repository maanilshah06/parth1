# Parth Weds Rutika — Prasang Planners

A ready-to-deploy Next.js wedding invitation website for GitHub + Vercel. You do **not** need to install VS Code, Node.js, or React on your laptop to deploy it through GitHub and Vercel.

## Wedding dates
- **10 February 2027 (Wednesday):** Mehendi and Haldi
- **11 February 2027 (Thursday):** Wedding ceremony
- **12 February 2027 (Friday):** Reception

Event timings and venue addresses are intentionally marked as forthcoming where not provided. Update them once confirmed.

## Deploy without installing software
1. Download and unzip this folder on your laptop.
2. Create a new repository on GitHub.
3. On the repository page choose **Add file → Upload files**. Upload the *contents* of this folder (so `package.json`, `app/`, and `public/` appear at the repository root, not inside an extra nested folder). Commit the upload.
4. Go to https://vercel.com/new, import that GitHub repository, and click **Deploy**.
5. In Vercel, keep the framework preset as **Next.js** and leave Build Command and Output Directory on their defaults. No environment variables are required.

Vercel installs the dependencies and builds the website in its cloud; your laptop does not need Node.js, React, or VS Code.

## Included features
- Large couple-name hero and countdown to 11 February 2027
- Three-day event schedule with individually themed Mehendi, Haldi, Wedding Ceremony and Reception cards
- Guest information / “Things to know” section inspired by the supplied Framer reference
- RSVP form, email contact, and WhatsApp contact link
- Prasang Planners logo and contact details
- Responsive design; no photo gallery section

## Important notes
- The RSVP form opens the visitor's email app with a prepared message. It does **not** save responses to a database.
- Venue and exact event timings have not been provided, so the page says these details are coming soon.
- The npm warning `Unknown env config "cache-dir"` comes from an npm environment/config setting on the build system, not from this website's source. It is a warning rather than a build failure. The old Next.js version has been upgraded to a patched release.
