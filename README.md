# Personal Google Drive Sync OAuth website

Static homepage and privacy policy for a privately configured rclone OAuth client.
This is not the official rclone project's website or shared OAuth application.

## Google Auth Platform → Branding

- Application home page: https://thetriumphantfox.github.io/google-drive-sync-oauth-site/
- Application privacy policy link: https://thetriumphantfox.github.io/google-drive-sync-oauth-site/privacy.html
- Authorized domain: `thetriumphantfox.github.io`

Save Branding, then open Audience and publish the app. An unverified private-use
app can still show an unverified-app consent warning. These pages do not claim
Google verification or eliminate OAuth approval requirements.

## Contents and deployment

- `index.html`: homepage
- `privacy.html`: privacy policy
- `style.css`: local stylesheet, no external scripts or analytics
- `.nojekyll`: serve as a plain static website

GitHub Pages deploys the repository root on branch `main`. Public files contain
no OAuth credentials, tokens, private Drive data, or account email addresses.
Do not add such data to this repository.

The actual sync commands and configuration are managed separately. Their local
operations guide is at `~/google-drive-sync/README.md` and is not published here.
