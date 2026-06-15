IMAGES FOLDER — mathias-sedo.com
=================================

Drop your image files in this folder, then update index.html.

HOW TO SWAP IN REAL IMAGES
---------------------------
In index.html, each image slot looks like this:

    <!-- <img src="images/installation-01.jpg" alt="Projection Study #1, 2024"> -->
    <div class="ph" style="background:..."></div>

To replace a placeholder:
  1. Add your image file here  (e.g. installation-01.jpg)
  2. Uncomment the <img> line  (remove <!-- and -->)
  3. Delete the <div class="ph"> line below it
  4. Update the filename and alt text if needed

EXPECTED FILES
--------------
Installations / Projection:
  installation-01.jpg  (landscape)
  installation-02.jpg  (portrait)
  installation-03.jpg  (portrait)
  installation-04.jpg  (square)
  installation-05.jpg  (landscape)
  installation-06.jpg  (portrait)

Photography:
  photo-01.jpg through photo-09.jpg  (all portrait / 2:3)

Shop prints:
  print-01.jpg through print-04.jpg  (4:5 ratio works best)

TIPS
----
- JPG or WebP both work well; WebP is smaller for the web
- Aim for 1800–2400px on the long edge for full-screen quality
- Keep file sizes under ~500 KB for fast loading (compress with squoosh.app)
- Use lowercase filenames with hyphens, no spaces
