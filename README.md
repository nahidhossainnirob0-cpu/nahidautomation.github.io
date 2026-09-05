# Nahid Hossain Nirob — AI Automation Portfolio

## Run locally
1. Install Node.js LTS.
2. Open terminal in this folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL Vite gives you.

## Contact form
GitHub Pages is static. The included form is prepared for Formspree.
Open `src/main.tsx` and replace:
`https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID`
with your Formspree endpoint. Do not put private API keys in frontend code.

## GitHub Pages
The repository includes `.github/workflows/deploy.yml`. Push the project to GitHub, then in Settings → Pages choose GitHub Actions as the source. After the workflow finishes, the site will be published at your GitHub Pages URL.
