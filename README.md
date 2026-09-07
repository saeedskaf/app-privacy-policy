# SuperDriver – Delivery Hero — Legal Pages

Public legal pages for the **SuperDriver – Delivery Hero** Android/iOS app
(`com.narj.superdriverapp`), published by Super Driver.

Served with GitHub Pages at:

| Page | URL |
|---|---|
| Privacy Policy | https://saeedskaf.github.io/app-privacy-policy/ |
| Account Deletion | https://saeedskaf.github.io/app-privacy-policy/delete-account.html |

Both URLs are referenced from the Google Play Console listing and the
Data safety form. **Do not rename, move or delete this repository, and do not
disable GitHub Pages** — doing so breaks the links declared to Google Play and
puts the app's publishing status at risk.

Both pages are available in English and Arabic via the language toggle.

Contact: info@superdriverapp.com

## Important

`privacy-policy.html` is the URL actually registered as the Privacy Policy in the
Google Play Console store listing, so it is a **full copy** of `index.html`, not
a redirect — an automated policy check must find the real policy text there.
**When you edit the privacy policy, update `index.html` and `privacy-policy.html`
together** (`cp index.html privacy-policy.html`).

## Alias pages

To survive any older URL that may still be recorded in Play Console or
elsewhere, these aliases redirect to the two canonical pages:

- `privacy.html`, `privacy_policy.html` → `index.html`
- `delete.html`, `delete_account.html`, `account-deletion.html`, `delete-account/` → `delete-account.html`

`404.html` catches anything else and links to both canonical pages, so no URL
under this repository can return a bare 404 to a Google Play reviewer.
