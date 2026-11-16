# Beach wedding invitation site

This is a static deployment package made from the supplied `view-source` HTML for the Beach wedding invitation demo.

## Deploy to Netlify

1. Create a GitHub repository and upload the files in this folder (`index.html`, `netlify.toml`, and this README) to its root.
2. In Netlify, choose **Add new site → Import an existing project**.
3. Connect GitHub and select the repository.
4. Leave **Build command** empty and set **Publish directory** to `.` (the repository root).
5. Deploy.

You can also test/deploy without GitHub by dragging this folder (or its ZIP contents) into Netlify's manual deploy area.

## Important notes

- The original page is a Framer-published page. Its layout, scripts, fonts, and many images are still loaded from the original `framerusercontent.com` CDN. This keeps the supplied design close to the source, but it is not a fully self-contained export; if the original Framer assets are removed or changed, some parts may stop working.
- The supplied source contains demo wedding details (Abhishek and Kanika, dates, venues, etc.). Edit those in `index.html` before publishing if you want your own invitation.
- The third-party PixelFlow tracking snippet and the source site's canonical URL have been removed from this deployment copy.
- You need to use your own rights/permission for the design, text, and media before publishing publicly.
