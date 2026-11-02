# Southern Africa El Niño Digital Twin

An Earth observation-driven digital twin framework for monitoring and predicting El Niño impacts on climate, water security, agricultural productivity, ecosystems and groundwater recharge across Southern Africa.

## Files
- `index.html` — website structure and content
- `style.css` — responsive layout and visual styling
- `app.js` — map, charts, navigation and illustrative scenario explorer

## Run locally
Open `index.html` in a modern browser. An internet connection is required for the external MapLibre, Chart.js and OpenFreeMap resources.

## Publish with GitHub Pages
1. Create a public GitHub repository, for example `southern-africa-el-nino-digital-twin`.
2. Upload all three files (`index.html`, `style.css`, `app.js`) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. After deployment, open the GitHub Pages URL shown in the Pages settings.

## Scientific and operational status
This is a front-end research prototype. It does not connect to live Earth observation data, execute trained AI models or run a calibrated hydrological model. Map extent, chart values and scenario scores are illustrative. Production use requires secured data services, validated model outputs, uncertainty reporting and documented data provenance.

Do not place Earth Engine credentials, service-account files, private API keys or passwords in this public repository. Connect privileged data processing through a secured backend.
