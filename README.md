Tailwind CLI setup for Classroom Team Game

Commands:
- npm install
- npm run build:css    # builds ./dist/styles.css from ./src/input.css
- npm run watch:css    # watch for changes and rebuild
- npm run dev          # watch css and serve the app at http://localhost:8080

The app now links to ./dist/styles.css instead of using the Tailwind CDN.


DEV Header
    <!-- Compiled Tailwind CSS (built with tailwindcss CLI) -->
    <link rel="stylesheet" href="https://blog.teacherjake.com/apps/scripts/tj-team-game/styles.css">
    <!-- PocketBase client (UMD) - using local copy from node_modules -->
    <script src="https://blog.teacherjake.com/apps/scripts/tj-team-game/node_modules/pocketbase/dist/pocketbase.umd.js"></script>
