# Sriram Raju — Portfolio

An interactive, anime-style portfolio that tells my career as a journey. A small traveler walks a hand-drawn landscape while the sky shifts from dawn to night, one chapter at a time. Projects live in a separate **Field Notes** panel, and contact details sit in an **About** panel.

The entire site is a **single HTML file** — no build step, no frameworks, no dependencies to install.

> **Live site:** _add your link here once deployed_ (see [Deploy](#deploy-to-github-pages) below)

---

## What's inside

- **One file, zero setup.** Everything (layout, styling, animation, content) lives in one `.html` file.
- **A guided journey.** Seven chapters reveal "what happened next" as you advance — by clicking **Continue**, tapping the glowing next lantern, or pressing the arrow keys.
- **Field Notes.** Selected projects as tap-to-open cards.
- **About panel.** A short profile with skills and contact links.
- **Works everywhere.** Desktop and mobile; the story card moves to full width on small screens.
- **Accessible.** Keyboard navigation (arrows / space / esc) and automatic respect for the "reduce motion" setting.

The only thing loaded from the internet is two Google Fonts. Open the file offline and it still runs; the fonts simply fall back to system defaults.

---

## View it locally

No tools required.

1. Download the `.html` file from this repository.
2. Double-click it. It opens in your default web browser.

That's the whole process — there is nothing to install or run.

---

## Edit your content (no coding needed)

All of the wording lives in clearly labeled, commented blocks near the top of the file. You only ever change the text **between the quotation marks** — leave the quotes, commas, and labels exactly as they are.

1. Right-click the `.html` file and choose **Open with** a plain text editor (Notepad on Windows, TextEdit on Mac, or the free [VS Code](https://code.visualstudio.com/)).
2. Use Find (`Ctrl/Cmd + F`) to jump to the block you want:
   - **`PROFILE`** — your name, role, location, short bio, email, and LinkedIn link.
   - **`JOURNEY`** — the seven chapters (each has a short eyebrow label, a title, and a paragraph).
   - **`PROJECTS`** — the Field Notes cards (tag, title, description).
   - **`ABILITIES`** — the skills shown in the About panel.
3. Edit the text inside the quotes.
4. **Save** the file and **refresh** your browser to see the change.

> **Tip:** The email and LinkedIn fields ship as placeholders. Swap in your real email before publishing.

---

## Deploy to GitHub Pages

This is the simplest free way to put the site online.

1. Rename the file to **`index.html`** and place it in the root of this repository. (GitHub Pages serves a file named `index.html` automatically at your site's main address.)
2. On GitHub, open the repository and go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set the branch to **`main`** and the folder to **`/ (root)`**, then click **Save**.
5. Wait about a minute, then refresh the Pages settings screen. GitHub will show the public URL (usually `https://your-username.github.io/your-repo-name/`).
6. Paste that link into the **Live site** line at the top of this README.

Other one-click options that work just as well, since this is a single static file: drag-and-drop to [Netlify Drop](https://app.netlify.com/drop), or [Cloudflare Pages](https://pages.cloudflare.com/).

---

## Built with

- Plain **HTML, CSS, and JavaScript** — no frameworks or build tools.
- **SVG** for the traveler character and the layered parallax landscape (original artwork, not copyrighted assets).
- **Google Fonts** — Fredoka (display) and Nunito (body).

A small design note for the curious: the world pans using CSS transforms while the sky stays fixed, and the page deliberately avoids browser storage (`localStorage`/`sessionStorage`) so it runs cleanly in any hosted or sandboxed environment.

---

## Before you publish

- Double-check the personal facts in the **`JOURNEY`** chapters — especially the early-career roles and the college project — and confirm your location and contact details.
- Give it one read with a "would I say this publicly?" lens to make sure no internal or confidential work details slipped in.

---

## License

Personal portfolio. The code is yours to reuse and adapt. If you want to let others reuse it too, consider adding an [MIT license](https://choosealicense.com/licenses/mit/).
