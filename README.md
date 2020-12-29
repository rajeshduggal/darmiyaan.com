# darmiyaan
Requires hugo extended version.
For optimizing the site for production, use hugo --minify -e production
To test the production build locally: hugo --minify -e production -d public
Url navigation leverages: https://get.foundation/sites/docs/magellan.html

Steps to build:
```bash
hugo mod npm pack
npm install
hugo server
```
