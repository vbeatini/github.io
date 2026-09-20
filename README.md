# vbeatini.github.io
personal website
-- in index, check the h2 style, shall be same as elsewhere
check portability in mobile
add a dropdown in teaching, and photos
add projects
add practice



maybe add visual network
if opportune for mobile, consider horizontal bands, maybe light cyano and bronze


ADDING IMAGES (research page):
1) Best size/proportions for new images:
Landscape orientation, ideally around 3:2 or 4:3 (e.g. 1400x900). The frame is 240 px tall and scales images uniformly, so wide-ish photos fill it best; tall/portrait shots will appear small with grey bands.
Resolution ~1400 px wide, JPG. Anything 1000-1600 px wide is fine.
2) Adding an image yourself takes two steps:
- Drop the JPG into assets/images/research/<pillar-folder>/ (lowercase-hyphen name, e.g. new-prototype.jpg).
- Open research.html, scroll to the <script> block at the bottom, find the galleries object, and add one line inside that pillar's list:
  'assets/images/research/reversible-adaptive/new-prototype.jpg',
Keep the quotes and the trailing comma. To change which image shows first in a slider, either put your line first in the list, or change that slider's <img src="..."> near the top of the page. Replacing a photo = swap the file with the same name, no code change.
