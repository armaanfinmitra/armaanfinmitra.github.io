Armaan FinMitra — website update (v4, 21 Nov 2026)
===================================================

WHAT CHANGED IN v4
  * Every trace of the old name "Armaan Shop" is gone. The schema markup
    listed it as an alternate name; that line is removed. The site now
    carries only "Armaan FinMitra".
  * Still included from v3/v2: LocalBusiness schema, FAQ section with
    FAQPage schema, address block, map, directions button, opening hours
    (Mon-Sat 10:00 am - 8:00 pm, Sunday closed), footer NAP, robots.txt,
    sitemap.xml.

HOW TO UPLOAD (2 minutes)
  1. Open https://github.com/armaanfinmitra/armaanfinmitra.github.io
  2. Click "Add file" -> "Upload files".
  3. Drag all three files in. index.html replaces the old one.
  4. Commit.

VERIFY IT WORKED (30 seconds)
  Open the repo, click index.html, press Ctrl+F and search "Visit the office".
  If it is there, the upload landed. Then open https://armaanfinmitra.github.io
  in a private window.

GOOGLE SEARCH CONSOLE
  Add property -> URL prefix -> https://armaanfinmitra.github.io/
  Verify with the HTML file (upload it to the repo the same way).
  Then submit sitemap.xml and request indexing.

  Once impressions appear (2-4 weeks), Performance -> Add filter -> Query ->
  Custom (regex) -> paste:
  ^(who|what|why|how|when|where|which|can|does|do|is|are|should|will|could|would)\b
