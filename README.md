# almanac-site

Public site for [Almanac](https://play.google.com/store/apps/details?id=app.almanac): home
page, privacy policy and account deletion route. Served by GitHub Pages at
<https://taha-lakdawala.github.io/almanac-site/>.

These pages are the addresses registered with:

- **Google Play** — privacy policy (`privacy.html`) and data deletion (`delete-account.html`).
- **Google Cloud** — the OAuth consent screen's home page (`index.html`) and privacy policy,
  for Sign in with Google in project `almanac-509320`.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page: what the app is, what is stored where. |
| `privacy.html` | Privacy policy. Update the effective date whenever it changes. |
| `delete-account.html` | How to delete the account, in the app or by email. |
| `style.css` | Tokens mirror `src/theme/tokens.ts` in the app repo. |
| `app-icon.png` | The app icon, used as the favicon and brand mark. |
| `.nojekyll` | Serve the files as they are, without Jekyll. |

Plain HTML and CSS, no build step. Edit and push to `main`; Pages redeploys within a minute.

Keep this in step with the app: if what syncs to the account changes, the privacy policy has
to change with it.
