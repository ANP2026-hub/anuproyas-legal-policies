ANUPROYAS — TRUST & SUPPORT CENTRE
GitHub Pages deployment package
Custom domain: policies.anuproyas.com
Repository expected: anuproyas/anuproyas-legal-policies

CLEAN PUBLIC ROUTES
/                         Trust & Support Centre
/contact-support/
/help-faqs/
/privacy-policy/
/terms-conditions/
/parents-consent/
/refund-policy/

DEPLOY
1. Open the existing GitHub repository:
   https://github.com/anuproyas/anuproyas-legal-policies
2. Keep a backup/download of the current repository before replacing files.
3. Upload the CONTENTS of this package to the repository root (not the ZIP itself).
   Keep the folder names and index.html files exactly as provided.
4. Commit the files to the branch configured for GitHub Pages (normally main).
5. In Settings > Pages, select Deploy from a branch, choose main and /(root), then Save.
6. In Settings > Pages > Custom domain, enter policies.anuproyas.com and Save.
   GitHub should retain/create the CNAME file in the published source.
7. Enable Enforce HTTPS after GitHub reports the certificate is ready.

DNS RECORD
At the DNS provider for anuproyas.com, add:
Type: CNAME
Name/Host: policies
Target/Value: anuproyas.github.io
TTL: Auto (or provider default)

Do not change the existing @ or www records. Do not add a second conflicting
CNAME for the same host. If a policies record already exists, inspect it before
changing it.

IMPORTANT
- This package is prepared from the six existing Anuproyas HTML page drafts.
- It does not publish itself to GitHub and does not alter DNS.
- GitHub repository and DNS provider access are not connected in this workspace.
- After deployment and DNS propagation, test all six HTTPS routes and mobile layout.
- The content remains general policy drafts, not legal advice. Confirm actual
  data practices, payment/refund terms and child-consent operations before relying on them.
