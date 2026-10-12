AURELIA ESTATES — SCENE 02: DRONE FLY-IN
========================================
INPUT: User's 10-second, 1280x720, 24-fps MP4
OUTPUT: 96 chronological WebP frames, 1280x720, optimized for a scroll-controlled website.

FOLDER CONTENTS
  scene02/index.html             Standalone browser scroll demo
  scene02/frames/frame_0000.webp ... frame_0095.webp
  scene02/CLAUDE_PROMPT.txt      Ready-to-paste Claude integration prompt

HOW TO TEST
1. Extract the ZIP (do not open index.html while it is still compressed).
2. Open scene02/index.html in Chrome.
3. Scroll DOWN to advance the drone shot, scroll UP to reverse it.

HOW TO HOST WITH AN EXISTING SCENE 01 GITHUB PAGES REPOSITORY
1. Keep all Scene 01 files unchanged.
2. Upload the entire `scene02` directory to the ROOT of the same GitHub repository.
   It must remain scene02/frames/frame_0000.webp, ..., scene02/frames/frame_0095.webp.
3. GitHub's browser file-upload limit may require 2 batches if more than 100 files are selected.
   This package has 99 files inside `scene02`, but count any extra files you add.
4. After the commit and GitHub Pages publishing, check these two sample URLs:
   https://YOURNAME.github.io/YOURREPO/scene02/index.html
   https://YOURNAME.github.io/YOURREPO/scene02/frames/frame_0000.webp
   (Replace YOURNAME and YOURREPO; your existing Pages setup must already serve the repository.)
5. Open scene02/CLAUDE_PROMPT.txt and replace [PASTE ... URL] with the real frames base URL.
6. Paste the full prompt into the SAME Claude chat where AURELIA Scene 01 works.

IMPORTANT
* Do not upload only the .ZIP and assume Claude can fetch a local archive: the 96 image URLs must
  be reachable by the published website for the integration to work.
* The 96 frames are intentionally sampled from the 240-frame video for reasonable web performance.
* This is a 96-frame animation, NOT an MP4 autoplay element.
* The video depicts a concept building. Confirm property accuracy before public use.
