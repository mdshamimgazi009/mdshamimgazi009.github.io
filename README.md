# MD. Shamim Gazi — Academic Website

A responsive, single-page academic portfolio designed for GitHub Pages.

## Publish it on GitHub

1. Sign in to GitHub as `mdshamimgazi009`.
2. Create a **public** repository named exactly:
   `mdshamimgazi009.github.io`
3. Extract this ZIP file on your computer.
4. Upload the contents of this folder (not the ZIP itself) into the repository:
   - `index.html`
   - `assets/style.css`
   - `assets/script.js`
   - `README.md`
5. Commit the files to the `main` branch.
6. Open repository **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main` and folder `/ (root)`, then Save.
9. After GitHub finishes publishing, visit:
   https://mdshamimgazi009.github.io

Initial publishing may take several minutes.

## Personalize before or after publishing

Open `index.html` and search for `TODO`. Update these items:

- Replace `YOUR_EMAIL@example.com` with your professional email address.
- Replace the generic Google Scholar, ORCID and LinkedIn links with your actual profile URLs.
- Add your own professional photograph. The hero currently uses an initials placeholder. To add a photo:
  1. Upload an image such as `profile.jpg` into the repository root.
  2. In `index.html`, replace the `<div class="portrait-placeholder"...>` block with:
     `<img class="profile-photo" src="profile.jpg" alt="MD. Shamim Gazi">`
  3. Add this to `assets/style.css`:
     `.profile-photo { width: 100%; height: 285px; object-fit: cover; display: block; }`
- Add a CV PDF after you have a final public version. Upload it to the repository and add a link to it.
- Verify the education dates, research descriptions, skills and experience before making the website public.

## Edit later

You can edit `index.html`, `assets/style.css` or `assets/script.js` directly on GitHub using the pencil/edit option. Commit the changes; GitHub Pages republishes the site automatically.

## Notes

- This website is static HTML, CSS and JavaScript. No paid hosting or build tools are required.
- Google Fonts are loaded from Google Fonts when visitors have internet access; the page still has fallback fonts.
- Do not publish private contact details, unpublished confidential data, passwords, or restricted laboratory information.
- Check every statement and link for accuracy before sharing the website with supervisors or institutions.
