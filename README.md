# Ocean Shallows

Een tropische zee van bovenaf in WebGL (Three.js r128): rimpelingen, lichtspel op de bodem, een strand met golven, en roggen en kwallen die je in zee kunt gooien.

Live at https://ocean.rubenmuller.nl. Every push to `main` uploads `index.html` to the Plesk hosting over FTPS
(see `.github/workflows/deploy-plesk.yml`). The workflow needs three repository secrets:
`FTP_SERVER`, `FTP_USERNAME` and `FTP_PASSWORD`, for an FTP account whose home folder is the subdomain's document root.
