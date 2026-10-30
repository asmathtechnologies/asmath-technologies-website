ASMATH TECHNOLOGIES WEBSITE

Static GitHub Pages site. No build step or external runtime libraries are required. Upload the files in this folder to the configured GitHub Pages publishing root. Keep the supplied assets folder beside index.html.

FILES
- index.html: homepage, services, consultation form UI and browser-based Ask Asmath chatbot.
- privacy.html: current privacy notice.
- 404.html: GitHub Pages not-found page.
- robots.txt and sitemap.xml: basic discovery files.
- assets/: supplied logos and favicon.

CONTACT FORM
Frontend validation, consent, submission status, pending-state duplicate prevention and a honeypot are present. The form is intentionally not connected. Set FORM_ENDPOINT in index.html to a verified HTTPS endpoint configured to deliver to info@AsmathTechnologies.com, then test success, validation and failure cases before advertising online submission. Do not put credentials or secret API keys in the frontend. Until configured, the page tells visitors to email directly.

CHATBOT
Ask Asmath is a rule-based assistant; it is not AI and does not send conversations to a server. It includes service questions, an email handoff and contact-form guidance. Keyboard open/close and Escape behavior are supported.

PUBLISH
The GitHub repository was not present in this workspace, so no commit or deployment was made. In your existing repository, preserve any CNAME file and other Pages configuration, copy the files above into the existing published root, commit and push using your normal workflow, then verify the live HTTPS domain and form endpoint. Confirm service descriptions and privacy practices before publishing.
