# Going Public: vallhundcybernetics.com in ~20 minutes (free)

Everything you need is in the `Public_Site_GitHub` folder: `index.html` (the 3D viewer),
`CNAME`, and `README.md`. No code knowledge required — this is all clicking.

## Part 1 — GitHub account + repo (~5 min)

1. Go to **github.com** → Sign up. Suggested username: **vallhund-cybernetics** (or
   **battlebuddy-project** if taken). Use your pm.me email. Turn on 2FA with your
   authenticator app, same drill as everything else.
2. Click **+** (top right) → **New repository**.
   - Name it exactly: **vallhund-cybernetics.github.io** (your username + `.github.io` —
     this special name makes it a website automatically). Public. Don't add any starter files.
3. On the new empty repo page, click **"uploading an existing file"**.
4. Drag in all three files from `Public_Site_GitHub`: `index.html`, `CNAME`, `README.md`.
   (`index.html` is ~6 MB — the upload takes a minute.)
5. Click **Commit changes**.

## Part 2 — turn on the website (~2 min)

1. In the repo: **Settings → Pages** (left sidebar).
2. Under "Build and deployment", Source should say **Deploy from a branch**, branch **main**,
   folder **/ (root)**. Save if it isn't already.
3. Within a few minutes, `https://<username>.github.io` shows the 3D arm. That link works
   immediately — the custom domain is the next part.

## Part 3 — point the domain at it (~10 min, then wait)

In **Namecheap → Domain List → vallhundcybernetics.com → Advanced DNS**, delete any
parking records and add these five:

| Type  | Host | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | \<username\>.github.io. |

Back in GitHub: **Settings → Pages → Custom domain** → type `vallhundcybernetics.com` →
Save. Once the DNS check passes (minutes to a few hours), tick **Enforce HTTPS**.

Done. The arm model is live at your own domain, free hosting, HTTPS, no monthly cost.

## What stays private — permanent rule

The repo and site carry the build only: the viewer, renders, and later the build-log.
Never into the public repo: dollar figures, grant strategy or applications, VA benefit
details, partner names before a yes, personal address. "Not hiding anything" applies to
the engineering — the business file stays in the folder.

## Later (not today)

- Build-log posts can live on this same site as simple pages — each December clip, each
  bench photo. The repo history itself becomes the public timeline.
- When outreach emails go out after this is live, the attachment can become a link:
  "interactive model at vallhundcybernetics.com" — no 6 MB attachment needed.
- X profile website field: vallhundcybernetics.com.
