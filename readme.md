# bric-lungs doc
This repository hosts the API documentation for the BRIC-LUNGS project.

## deploy
1. Edit the openapi.yaml template as needed
2. Run `npx redoc-cli bundle openapi.yaml && mv redoc-static.html index.html && sed -i '7 i \ \ <link rel="icon" type="image/png" href="favicon.png"/>' index.html`