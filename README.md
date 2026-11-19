# Style Sync
Open `index.html` in a browser (Chrome/Edge/Firefox). Sign in with "Try demo account" or register.

- index.html – User authentication, merged into the Old Money wardrobe page (sign in / register form beside the wardrobe; the doors open on success)
- app.html – 11-module app on a hanging-rail wardrobe theme (Ice Silver / Deep Aubergine / Marigold)
- pages/outfit_recommendations.html – your chatbot + dice file (Outfit Engine); its "Save outfit" now also feeds Saved Outfits
- js/core.js (colour science, scoring, outfit builder), js/modules.js (all modules), js/auth.js

Notes: data is stored in the browser's localStorage (demo-grade auth, no server). Weather uses the free Open-Meteo API when online; fonts load from Google Fonts.
