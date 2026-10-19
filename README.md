THE IMAGE LAYOUT - Animated Portfolio (editable source)
========================================================

HOW TO OPEN
  Double-click index.html. It opens in Chrome / Edge / Safari.
  Keep the "img" folder next to index.html, otherwise the photos will not show.

IF ANIMATIONS DO NOT MOVE
  Some laptops have "Show animations in Windows" (or Reduce motion) switched off.
  The page then shows a bar at the bottom: click "Turn on animations".
  To fix it for good on Windows: Settings > Accessibility > Visual effects >
  Animation effects = On.

HOW TO EDIT TEXT
  Open index.html in any editor (VS Code, Notepad++, even Notepad).
  Search for the word EDIT. Those comments mark the parts you will change most:
    - main title and tagline        (HERO section)
    - "5+ years of experience"      (change data-to="5" and the 5 next to it)
    - layout cards, sizes, captions (ALBUM DESIGN section, one <li> per card)
    - bride / groom / haldi text    (ALBUM STORIES, one .panel per tab)
    - process steps                 (PROCESS section)
    - phone, email, Instagram       (CONTACT section)

HOW TO SWAP A PHOTO
  1. Put your new image in the img folder (JPG, about 1800px wide works best).
  2. In index.html, replace the file name in src="img/..." and data-src="img/...".
     Keep width and height numbers matching the new image.

HOW TO CHANGE COLOURS / FONTS
  Everything is at the top of index.html inside :root { ... }.
    --bg      page background        --fg-strong  headings
    --fg      body text              --accent     maroon highlights
  The dark theme colours are the two blocks right below it.
  Fonts: Italiana (headings) and Jost (text), loaded from Google Fonts.

HOW TO PUT IT ONLINE (free)
  Drag this whole folder onto netlify.com/drop, or upload it to GitHub Pages / Vercel.
  You then get a link to share with clients.
