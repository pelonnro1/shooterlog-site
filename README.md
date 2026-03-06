# ShooterLog Public Site (GitHub Pages)

This folder is a ready-to-publish static site for App Store / Play Store metadata links:

- Privacy policy
- Terms of use
- Data storage and backup terms
- Support page

## Recommended setup (separate repo)

1. Create a new GitHub repo, for example `shooterlog-site`.
2. Copy all files from this `site/` folder into that repo root.
3. In GitHub: `Settings -> Pages`.
4. Set source to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Wait for publish, then verify:
   - `/privacy/`
   - `/terms/`
   - `/data-processing/`
   - `/support/`

## Store metadata URLs

Use these in App Store Connect and Play Console:

- Privacy Policy URL: `https://<your-user>.github.io/shooterlog-site/privacy/`
- Support URL: `https://<your-user>.github.io/shooterlog-site/support/`
- Marketing URL (optional): `https://<your-user>.github.io/shooterlog-site/`

## Keep content in sync

When app legal text changes, update both:

- In-app legal copy (`src/legal/*`, `docs/legal/*`)
- Public pages in this folder (`site/*.md`)
