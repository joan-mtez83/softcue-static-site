# softcue.app — static site

Plain HTML/CSS. No build step.

Files:
- index.html     landing page
- support.html   App Store "Support URL"
- privacy.html   App Store "Privacy Policy URL"
- terms.html     terms of use
- styles.css, favicon.svg

Deploy to Porkbun Static Hosting: upload every file in this folder to the
web root via the Porkbun file browser or FTP. Or connect this folder as a
GitHub repo and use Porkbun's "GitHub Connect" for automatic deploys.

Before going live:
1. Create the email forward support@softcue.app in Porkbun (free), or change
   every "support@softcue.app" in the HTML to joan.mtez@softcue.app.
2. Read privacy.html and terms.html once. They describe the app as specced
   (local scripts, Sign in with Apple, Supabase backend, Anthropic rewrites).
   If the final build differs, change the text.
