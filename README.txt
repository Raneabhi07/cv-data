Metadata Governance and Solution - local copy
=============================================

HOW TO RUN
  FIRST unzip the whole folder (do not open index.html from inside the zip viewer).
  All pictures are built into index.html, so it is a single self-contained file.
  Easiest:  double-click index.html (opens in your browser).
  Better:   run start.bat (Windows) or start.sh (Mac/Linux). It starts a tiny local web server
            and you open http://localhost:8000 . Needs Python 3 installed.
  Internet is only needed for the Google Font; without it the page uses system fonts.

EDITING AND SAVING
  Click the pencil icon (top right) to open Configure. Press Save after editing a tile.
  Saved content and pictures are kept in THIS browser (browser storage), so they are still
  there when you reload. Use the same browser and the same way of opening the page
  (double-click vs localhost) each time - they keep separate storage.
  The Export button in Configure downloads your text content as a JSON file (a backup;
  pictures are not included).
  To go back to the original content: clear this site's data in your browser.
  Pictures are stored in browser storage (about 5 MB total), so use a few small ones.

If Save shows an error about storage, your browser is blocking storage for local files:
open the page through start.bat / start.sh instead.
