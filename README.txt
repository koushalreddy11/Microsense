MicroSense v17 - Local TWA Project (Bubblewrap)

Package name: com.koushal.microsense
Offline domain placeholder used: https://koushal.microsense.local

How to build APK (one command):
1) Install Node.js and npm.
2) Install Bubblewrap:
   npm i -g @bubblewrap/cli
3) From this folder (twa-project), run:
   bubblewrap init --manifest twa-manifest.json
   bubblewrap build

Notes:
- The project bundles the web app under twa-project/www
- The TWA will use the placeholder origin specified in twa-manifest.json
- The produced APK will load the local assets bundled in the app
