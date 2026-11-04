# Ocean Shallows

A top-down tropical sea in WebGL (Three.js r128): ripples, caustics, a beach with swash, and rays and jellyfish you can throw in.

Live at https://ocean.rubenmuller.nl. Every push to `main` uploads `index.html` to the Plesk hosting over FTPS
(see `.github/workflows/deploy-plesk.yml`). The workflow needs three repository secrets:
`FTP_SERVER`, `FTP_USERNAME` and `FTP_PASSWORD`, for an FTP account whose home folder is the subdomain's document root.
