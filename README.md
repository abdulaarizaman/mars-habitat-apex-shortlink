# MARS HABITAT APEX short redirect

This is a tiny static Netlify site that redirects visitors to:
https://mars-habitat-apex-visitor.onrender.com

## Deploy
1. Create a new site in Netlify and choose manual deploy, or upload this folder's files using Netlify Drop.
2. After deploy, open Site configuration / Domain management and change the Netlify site name to a short available name (for example `mhs-review` if available).
3. Test the assigned `https://YOUR-SITE-NAME.netlify.app` address on a phone.
4. Only after the short URL works, regenerate the poster QR to encode that short URL and print the short URL as text below it.

Files: `index.html` provides a redirect and a fallback link; `_redirects` configures a server-side permanent redirect.
