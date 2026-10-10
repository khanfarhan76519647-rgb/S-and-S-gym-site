S&S GYM — GITHUB PAGES PRODUCTION PACKAGE

This ZIP contains the ready-built static website. Upload the CONTENTS of this folder to the top level of your GitHub repository (the index.html file must be at the repository root). Do not upload the ZIP itself as the website.

PUBLISH FROM THE GITHUB WEBSITE
1. Download and extract this ZIP on your computer.
2. Create or open the repository where you want the website. Make sure the repository is public if your GitHub plan requires a public repository for Pages.
3. In the repository, select Add file → Upload files. Drag in all extracted files and folders, including index.html, assets, images, favicon.svg, robots.txt, and .nojekyll. Keep their folder structure.
4. Commit the uploaded files to the main branch.
5. Open Settings → Pages. Under Build and deployment, choose Deploy from a branch, choose main and /(root), then Save.
6. When GitHub finishes its Pages deployment, open the site URL shown in Settings → Pages.

IMPORTANT: THIS IS A STATIC GITHUB PAGES VERSION
GitHub Pages does not run the S&S Gym registration API or database. Join and plan buttons open WhatsApp with a message to the gym; the website does not save membership registrations. The enquiry form prepares a WhatsApp message and sends nothing until the visitor chooses Send in WhatsApp.

All URLs in this package are relative, so the same files can be used at a GitHub Pages repository URL or a custom domain. The fonts load from Google Fonts when the visitor has an internet connection.

GitHub's instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
