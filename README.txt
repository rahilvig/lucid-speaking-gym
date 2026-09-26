LUCID - install on your iPhone

iPhones only install web apps from a web address, so host these files once (free), then add to your Home Screen.

OPTION A - GitHub Pages (can be done entirely on your phone)
1. Unzip this file in the Files app (tap it).
2. Sign in at github.com in Safari, create a new PUBLIC repository (e.g. "lucid").
3. In the repo tap "Add file" > "Upload files" and select ALL files from the unzipped folder
   (index.html, manifest.webmanifest, sw.js, icon-180.png, icon-192.png, icon-512.png). Commit.
4. Repo Settings > Pages > Source: "Deploy from a branch", branch "main", folder "/ (root)". Save.
5. After a minute or two your app is at https://YOUR-USERNAME.github.io/lucid/

OPTION B - Netlify Drop (needs a computer)
Drag the unzipped folder onto app.netlify.com/drop and use the https link it gives you.

THEN, ON YOUR iPHONE
1. Open the https link in SAFARI.
2. Tap Share > "Add to Home Screen" > Add.
3. Open Lucid from the Home Screen icon. It runs full screen, works offline,
   and saves all progress on your phone.

TIPS
- Always open Lucid from the Home Screen icon: that copy has its own storage.
- Settings > "Back up progress" saves a backup file to Files/iCloud. Restore it on a new phone.
- Coach feedback is optional: paste an Anthropic API key in Settings.
- If live transcription doesn't pick you up, Settings > Keyboard dictation,
  or turn off Pause analysis and try again.
