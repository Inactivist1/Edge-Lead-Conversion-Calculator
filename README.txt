MOVER LEAD - OFFLINE IPHONE APP

Files (upload all of them, together, to the same folder):
  index.html             the app
  sw.js                  saves the app on the phone for offline use
  manifest.webmanifest   app name and icons for the Home Screen
  apple-touch-icon.png, icon-192.png, icon-512.png, icon-maskable-512.png

PUT IT ONLINE (GitHub Pages, free)
 1. Sign in at github.com and create a new public repository, e.g. "mover-lead".
 2. On the repository page: Add file > Upload files. Drag in every file above
    (not the folder itself) and click Commit changes.
 3. Settings > Pages. Under "Build and deployment", Source: Deploy from a branch,
    Branch: main, folder: / (root). Save.
 4. After a minute the page is live at https://<your-username>.github.io/mover-lead/
    (Netlify Drop at app.netlify.com/drop also works: drag the folder onto the page.)

PUT IT ON THE IPHONE
 1. With a signal, open that address in Safari. Let it load fully.
 2. Share > Add to Home Screen > Add.
 3. Open it once from the Home Screen icon while you still have a signal.
 4. Test: turn on Airplane Mode and open it again. It should calculate normally.

UPDATING LATER
 Edit the files, change VERSION in sw.js (e.g. mover-lead-v2), and upload again.
 Open the app once with a signal to pick up the new version.

Notes
 - Settings are saved on the phone only.
 - Fonts come from Google Fonts; if they weren't saved, the app uses system fonts.
 - iOS can clear saved web data for Home Screen apps you don't open for many weeks.
   If it ever opens blank with no signal, open it once with a signal to re-save it.
