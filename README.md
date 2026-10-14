# Timo public App Store support site

This folder contains **only public static pages**, not the Timo application source code.

## Publish

1. On GitHub create a new **Public** repository named `timo-app-site` under your account.
2. Upload only the files in this directory or push them from a **separate** Git repository. Never change `/Users/lzq/Project/Timo` to public.
3. GitHub repository Settings → Pages → Build and deployment → Deploy from a branch → `main` `/ (root)` → Save.
4. Wait for the Pages site to build, then verify these in a private browser window:
   - `https://jiliguluzhiquan.github.io/timo-app-site/privacy.html`
   - `https://jiliguluzhiquan.github.io/timo-app-site/support.html`
5. Set these verified URLs in App Store Connect's Privacy Policy URL and Support URL fields.

**Before publish:** review the policy for accuracy against actual server deployment, hosting logs and app capabilities. In particular, decide how you handle support reports without disclosing private data.
