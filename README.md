# privacy-policies

Privacy policies and legal documents for our published apps. Hosted via GitHub Pages with Jekyll (cayman theme).

## Structure

```
/                         → index.md (landing, lists all apps)
/tinywhales/privacy.md    → Tiny Cozy Critters
```

## Adding a new app

1. Create folder `<appname>/`
2. Add `<appname>/privacy.md` with front matter:
   ```yaml
   ---
   layout: default
   title: <App Name> — Privacy Policy
   ---
   ```
3. Add a link in `index.md`
4. Commit and push

## Live URLs

After enabling GitHub Pages (Settings → Pages → Branch: `main`, root):

- `https://<user>.github.io/privacy-policies/`
- `https://<user>.github.io/privacy-policies/tinywhales/privacy/`

Use the second form when filling App Store Connect's Privacy Policy URL.
