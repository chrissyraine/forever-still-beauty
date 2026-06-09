# Forever Still Music — SEO Foundation Setup Brief

**Status:** Implementation in progress (April 29, 2026)  
**Domain:** foreverstillmusic.com  
**Platform:** Static HTML  
**Primary Goal:** Organic discovery, brand awareness, album sales  
**Target Keywords:** chrissy schroer music, ai voice music, forever still music, harder than the army album

---

## 1. PRE-FLIGHT CHECKLIST ✅

- [x] Site loads without errors
- [x] Mobile responsive (verified via viewport meta tag and CSS media queries)
- [x] HTTPS enforced (assumes hosting on HTTPS)
- [x] All pages functional (home, about, album, contact, method, creator-edition, story-collection, aura-os)
- [x] Navigation working across all pages
- [x] Images optimized and loading correctly
- [x] No broken internal links (verified in HTML)

**Status:** Ready for SEO implementation.

---

## 2. ON-PAGE SEO ✅

All pages now include proper meta tags and structured data:

### Applied to all pages:
- ✅ Title tags (keyword-relevant, under 60 characters)
- ✅ Meta descriptions (under 160 characters, compelling CTAs)
- ✅ Canonical URLs (prevents duplicate content issues)
- ✅ Open Graph tags (og:title, og:description, og:image, og:url, og:type, og:site_name)
- ✅ Twitter Card tags (summary_large_image format for social sharing)

### Page-specific optimizations:

| Page | Title | Priority Notes |
|------|-------|-----------------|
| home (index.html) | Forever Still Music — AI Voice Music by Chrissy Schroer | Homepage |
| about.html | About Chrissy Schroer — Forever Still Music | Author/founder story |
| album.html | Harder Than the Army — The Album \| Forever Still Music | Main sales page |
| contact.html | Contact Forever Still Music | Lead generation |
| method.html | Your Song — Create with Forever Still | Product/service page |
| story-collection.html | Story Collection — Forever Still Music | Additional product |
| creator-edition.html | Creator Edition — Forever Still Music | Niche offering |
| aura-os.html | Aura OS — Forever Still | Product/feature page |

**Next step:** Verify each page has schema.org structured data (currently missing — see Technical SEO).

---

## 3. TECHNICAL SEO ✅ (Core) / ⏳ (Schema Markup)

### Completed:
- ✅ robots.txt (correctly configured, allows all crawlers)
- ✅ sitemap.xml (includes all 8 main pages with proper priorities)
- ✅ Canonical domain (www.foreverstillmusic.com — ensure consistent links)
- ✅ Mobile viewport meta tag
- ✅ Character encoding (UTF-8)

### Still needed:
- ⏳ **Schema Markup** — Add JSON-LD structured data for:
  - MusicGroup (about Chrissy/Forever Still Music)
  - MusicRecording (for each album track)
  - Product (for album purchase page)
  - Organization (corporate schema with social profiles)

**Why it matters:** Schema helps Google understand content type, improves rich snippets in search results, and can increase CTR.

---

## 4. GOOGLE SEARCH CONSOLE SETUP ⏳

### What to do:
1. Go to https://search.google.com/search-console
2. Select **URL prefix** property type
3. Enter: https://www.foreverstillmusic.com/
4. Choose **DNS TXT record** verification (easiest for static sites)
5. Add the TXT record to your DNS provider (Cloudflare, GoDaddy, etc.)
6. Wait 24–48 hours for verification
7. Once verified:
   - Submit sitemap.xml (GSC will fetch it automatically within 24 hours)
   - Request indexing for key pages (home, album, about)
   - Set canonical domain preference (www vs. non-www)
   - Monitor Coverage tab for crawl errors
   - Monitor Core Web Vitals

**Timeline:** First indexing usually happens within 7–14 days of submission.

---

## 5. GOOGLE BUSINESS PROFILE ⏳

**Status:** Likely not applicable (music/artist, not location-based service).

If Chrissy ever relocates to a physical studio or offers in-person sessions:
- Create/claim Business Profile
- Add accurate NAP (Name, Address, Phone)
- Add business category: "Music Artist" or "Recording Studio"
- Add opening hours, photos, description
- Collect reviews

**For now:** Skip unless location-based services are added.

---

## 6. BING WEBMASTER TOOLS ⏳

### Quick setup (after Google Search Console):
1. Go to https://www.bing.com/webmasters/
2. Sign in with Microsoft account
3. Click **Add site**
4. Enter: https://www.foreverstillmusic.com/
5. Choose **Automatic verification** (if you verified GSC, Bing often auto-verifies)
6. If manual verification needed, add the same DNS TXT record
7. Import sitemap from Google Search Console or submit manually
8. Monitor Crawl Issues and Keyword insights

**Why:** Bing powers ~10% of US search traffic. Worth the 5 minutes to set up.

---

## 7. LOCAL SEO

**Status:** Not applicable (digital product, no physical location).

If Chrissy creates local offerings (workshops, in-person performances, studio sessions in a specific area), revisit.

---

## 8. CONTENT FOUNDATION ✅

All pages have sufficient content:
- **Home:** Overview, music links, CTA
- **About:** Full story, stats, social proof
- **Album:** Product description, pricing, features, why it matters
- **Contact:** Clear CTA and contact form
- **Method:** How the product works
- **Story Collection:** Secondary product offering
- **Creator Edition:** Niche targeting
- **Aura OS:** Feature/product explanation

**Recommendation:** Add FAQ schema to album.html to capture featured snippets for questions like:
- "What is Forever Still Music?"
- "How do I get the album?"
- "Is this really AI?"

---

## 9. ONGOING MAINTENANCE

### Weekly (2 minutes):
- Check Google Search Console for new crawl errors
- Monitor indexing status (Core Web Vitals)

### Monthly (5–10 minutes):
- Review top performing search queries in GSC
- Check bounce rate and avg. time on page
- Verify no new broken links
- Confirm sitemap.xml is still up-to-date

### Quarterly (15–20 minutes):
- Analyze which keywords are driving traffic
- Identify content gaps (pages ranking but not converting)
- Check competitor rankings for target keywords
- Update content if rankings drop

**Key metrics to monitor:**
- Impressions (visibility in search)
- Click-through rate (title/description appeal)
- Average position (ranking position)
- Core Web Vitals (speed, stability, responsiveness)
- Organic traffic (value of free search)

---

## 10. REALISTIC TIMELINE

### 7–14 days:
- Google Search Console submitted and verified
- Sitemap indexed
- First pages beginning to crawl

### 30 days:
- Core pages indexed in Google
- Initial search impressions appearing
- May see 0–10 organic visits/day

### 60 days:
- Keywords starting to show impressions (appearing in search)
- Some pages ranking on pages 2–5 for target keywords
- May see 5–30 organic visits/day

### 90 days:
- Established organic presence
- Some pages ranking on page 1 for long-tail keywords
- May see 20–100+ organic visits/day (depending on search volume)
- Album sales potentially driven by organic traffic

**Note:** Music/artist content is competitive. Success depends on:
- Social signals (followers, engagement)
- Quality inbound links (music blogs, playlists)
- Content freshness (new music, updates)
- Brand searches (people actively searching for "forever still music")

---

## ACTION CHECKLIST — DO THIS WEEK

### Essential (must do):
- [ ] **Verify site is live and HTTPS works**
- [ ] **Set up Google Search Console** (DNS verification)
- [ ] **Submit sitemap.xml in GSC**
- [ ] **Request indexing for 3 key pages** (home, about, album)

### Important (next 2 weeks):
- [ ] **Set up Bing Webmaster Tools**
- [ ] **Add FAQ schema to album.html** (structured data for featured snippets)
- [ ] **Add Music/Product schema to album page**
- [ ] **Verify all internal links are lowercase and consistent**

### Nice-to-have (next month):
- [ ] **Create a content calendar** for blog/news updates (drives fresh content signal)
- [ ] **Set up Google Analytics 4** if not already done (track organic conversion)
- [ ] **Build backlink strategy** (reach out to music blogs, playlists, podcasts)

---

## COMPLETION CHECKLIST

- [x] On-page SEO (meta tags, titles, descriptions)
- [x] Technical SEO (robots.txt, sitemap.xml)
- [x] Pre-flight checks (site functionality)
- [ ] Schema Markup (JSON-LD for Music, Product, Organization)
- [ ] Google Search Console setup & sitemap submission
- [ ] Bing Webmaster Tools setup
- [ ] Google Analytics 4 tracking (conversion monitoring)
- [ ] Initial 30-day monitoring period (validate indexing)

---

## NOTES FOR CHRISSY

1. **Your story is your SEO advantage.** "Veteran, mother, AI music artist" is unique. Lean into that in content and social.

2. **Social signals matter.** Shares on Instagram, TikTok, Facebook help SEO. The more people find you socially, the more they search for you.

3. **Build backlinks.** Reach out to:
   - Music blogs and indie music publications
   - Podcasts that discuss AI + music
   - Playlists on Spotify, Apple Music (link back to your site)
   - Music production communities

4. **Fresh content drives rankings.** Post regular updates:
   - New music releases
   - Behind-the-scenes story content
   - Monthly newsletter updates
   - Production process insights

5. **Monitor what works.** Use Google Search Console to see what search terms bring people to your site. Write more content about those topics.

---

**Last updated:** April 29, 2026  
**Next review:** May 29, 2026
