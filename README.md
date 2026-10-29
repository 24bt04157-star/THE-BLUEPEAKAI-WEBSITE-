# BluePeakAI Website

A responsive, multi-page static website for BluePeakAI, built with HTML, CSS and vanilla JavaScript. It is designed for editing in VS Code and uploading to Hostinger shared hosting.

## Pages
- `index.html` — homepage, services overview, process and featured projects
- `services.html` — detailed services
- `work.html` — portfolio
- `why-us.html` — positioning, differentiators and working process
- `about.html` — founder story and contact links
- `contact.html` — contact details, project enquiry form and FAQ

## Run locally in VS Code
1. Extract the ZIP.
2. Open the `bluepeakai-website` folder in VS Code.
3. Install the VS Code extension **Live Server** (or use any static local server).
4. Right-click `index.html` and choose **Open with Live Server**.
5. Check each page, links, mobile navigation and the contact form.

You can also open `index.html` directly in a browser, but a local server is more reliable for testing.

## Contact form behaviour
The form currently validates fields in the browser and opens WhatsApp with a pre-filled project enquiry. The visitor reviews the message and manually presses Send. The form does **not** store submissions or send email in the background.

If you want submissions emailed or stored in a CRM without opening WhatsApp, connect a form backend/service or implement a server endpoint before launch.

## Deploy to Hostinger
1. In Hostinger hPanel, open **Websites** and choose `bluepeakai.in` → **Manage**.
2. Open **File Manager** and navigate to `public_html`.
3. Back up any existing site files before replacing them.
4. Upload the ZIP and extract it, or extract it locally and upload the *contents* of this folder into `public_html`.
5. Confirm `index.html` sits directly inside `public_html` (not inside an extra nested folder).
6. In hPanel, enable/verify SSL for `bluepeakai.in`.
7. Test `https://bluepeakai.in`, each page, mobile layout, WhatsApp links and the contact form on desktop and mobile.

The included `.htaccess` forces HTTPS for `bluepeakai.in` after SSL is active. If you are testing before SSL is ready, temporarily comment out the HTTPS redirect block.

## Before publishing
- Confirm that every portfolio project is approved for public display and accurately labelled as client work, a personal project or a demo.
- Confirm all live project URLs still work before publishing.
- Add real project screenshots and only verified client testimonials/results.
- Check that you have permission to publish each portfolio project.
- Test the form and all social links on the live domain.
- Custom domain and hosting costs are separate from project pricing, per BluePeakAI's terms.

## Editing brand details
- Global styles: `assets/styles.css`
- Mobile menu, reveal animation and contact form: `assets/script.js`
- Page content: the relevant `.html` file
- Brand icon: `assets/favicon.svg`

## Technology
- HTML5
- CSS3 (responsive layout and reduced-motion support)
- Vanilla JavaScript
- No build step or package installation required


Brand assets: `assets/bluepeakai-logo.jpg` is the supplied BluePeakAI logo and `assets/ayushi-shah-founder.png` is the supplied founder photo. The Why Us page is available at `why-us.html`.
