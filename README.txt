Armaan FinMitra — website update (v3, 21 Nov 2026)
===================================================

WHAT IS NEW IN v3
  * FAQ section on the page: 10 questions customers actually ask, in an
    accordion, with matching FAQPage schema so Google can read them.
  * Everything from v2 is still here: LocalBusiness schema, address block,
    opening hours (Mon-Sat 10:00 am - 8:00 pm, Sunday closed), map embed,
    directions button, robots.txt and sitemap.xml.

HOW TO UPLOAD (2 minutes, no command line)
  1. Open https://github.com/armaanfinmitra/armaanfinmitra.github.io
  2. Click "Add file" -> "Upload files".
  3. Drag all three files from this folder in. index.html replaces the old one.
  4. Type a commit message, click "Commit changes".
  5. Wait 1-2 minutes, open https://armaanfinmitra.github.io and scroll down.

------------------------------------------------------------------
STEP 2 — GOOGLE SEARCH CONSOLE (this is the method from the video)
------------------------------------------------------------------
The video's method only works AFTER Google has indexed the site and started
showing it in search. So do this first, then wait, then use the filter.

1. Open https://search.google.com/search-console and sign in.
2. Click "Add property".
3. Choose "URL prefix" (NOT "Domain" — a github.io subdomain cannot be
   verified as a domain property).
4. Type exactly:  https://armaanfinmitra.github.io/
5. Click Continue.
6. For verification choose "HTML file".
   Google gives you a file like google1a2b3c.html — download it, then upload
   that file to your repo the same way you uploaded these three files.
   Wait 1 minute, come back and click Verify.
7. Left menu -> Sitemaps -> enter "sitemap.xml" -> Submit.
8. Left menu -> URL Inspection -> paste https://armaanfinmitra.github.io/
   -> click "Request indexing".
9. Wait 1-3 weeks. Nothing in the Performance tab means anything before that.

------------------------------------------------------------------
STEP 3 — FIND THE QUESTIONS PEOPLE ASK (the actual "hack")
------------------------------------------------------------------
Once impressions start appearing:

1. Left menu -> Performance.
2. Click "+ Add filter" -> choose "Query".
3. In the dropdown pick "Custom (regex)".
4. Paste this exact line:

^(who|what|why|how|when|where|which|can|does|do|is|are|should|will|could|would)\b

5. Now the report shows only question searches that found you.
6. Click the "Queries" tab. Every row is a question a real person typed.
7. For each question you cannot answer well on the site, add a FAQ entry
   or a short page that answers it plainly.

That is the whole method. The filter is the easy part — the work is writing
the answer in the same words the person used.

------------------------------------------------------------------
STEP 4 — AFTER THAT
------------------------------------------------------------------
  * Post on Google Business Profile once a week.
  * Ask every customer for a review in the first month (target: 10-15).
  * Check the schema: https://search.google.com/test/rich-results
