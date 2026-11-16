# NOOBESAG

Persian browser-game portal using the original **Noobe Sag Divine v3** host page.

- Homepage: `index.html`
- Ghobaar 2: `games/ghobaar-2.html`
- Age of Shahanshahs: `games/age-of-shahanshahs.html`
- Host artwork: `assets/noobe-art-00.js` through `assets/noobe-art-08.js` (parts of the original inline artwork, reconstructed in the browser)

The two game buttons on the original homepage launch their independent HTML files in an in-page fullscreen overlay. Noobe Sag's offline build does not provide functioning server-side accounts, tournaments, or ranked player storage.

## Deployment

The `CNAME` file sets `www.noobsesag.com` as the custom domain. Enable GitHub Pages from `main` at repository root, set the custom domain to `www.noobsesag.com`, and configure Porkbun DNS (www CNAME to `memortal.github.io`; apex A records per GitHub Pages documentation). Publishing may require making this repository public on your GitHub plan.

Do not remove the `assets` folder: it contains pieces of the host-page image.
