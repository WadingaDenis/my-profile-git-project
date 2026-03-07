Fofung Denis Wadinga — Static Profile

This repository contains a single-page static profile `den-profile.html` and an `index.html` redirect.

Deploy to AWS Amplify (recommended):

1. Push this repository to GitHub (or connect your Git provider).

```bash
# from repository root
git add .
git commit -m "Prepare for Amplify: add index redirect and README"
# add your remote if needed
# git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

2. In the AWS Console go to AWS Amplify -> "Get started" -> "Host web app".
3. Choose your Git provider (GitHub, Bitbucket, GitLab, or CodeCommit) and connect the repo and branch.
4. Amplify will detect a static site; use the default build settings (no build commands required for plain HTML). Confirm and deploy.

Alternative: Manual deploy

- Zip the site files (index.html and den-profile.html) and upload via Amplify Console -> "Deploy without Git".

Notes

- Replace placeholder emails and links inside `den-profile.html` before publishing.
- If you later convert to React/Next.js, Amplify can build and deploy from the repo with a simple `amplify.yml` build spec.
