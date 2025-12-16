<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/temp/1

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Deploy to Production

To deploy this Vite React app to a hosting platform:

1. Build the app:
   `npm run build`

2. The `dist` folder will contain the production build.

3. Deploy the `dist` folder to your hosting provider (e.g., Vercel, Netlify, GitHub Pages).

For Netlify:
- Connect your repository
- Set build command: `npm run build`
- Publish directory: `dist`

For Vercel:
- Connect your repository
- Vercel will auto-detect Vite and build accordingly.

Note: For client-side API calls to Gemini, ensure your API key is handled securely (e.g., via environment variables on the hosting platform).
