# Your SEO Setup Checklist
### Forever Still Music — foreverstillbeauty.com

Everything the code can do has already been done. This document covers the steps only **you** can do — the ones that require logging into accounts. Work through these in order, one sitting if possible.

---

## Step 1 — Google Search Console

This is how you tell Google your site exists and get it indexed fast.

1. Go to **[search.google.com/search-console](https://search.google.com/search-console)**
2. Sign in with your Google account
3. Click **"Add property"** → choose **"Domain"** (not URL prefix — Domain covers www and non-www automatically)
4. Enter `foreverstillbeauty.com` (no www, no https://) → click **Continue**
5. Google will show you a **TXT record** to add to your DNS. It looks like: `google-site-verification=abc123xyz`
6. Log into wherever your domain is registered (likely GoDaddy, Namecheap, Squarespace, or Cloudflare)
   - Find DNS settings → Add a new record
   - Type: `TXT`
   - Name/Host: `@`
   - Value: paste the code Google gave you
   - TTL: default is fine
7. Back in Search Console, click **Verify** (may take a few minutes to propagate — try again in 10-15 min if it fails first time)
8. Once verified, click **Sitemaps** in the left menu → enter `sitemap.xml` → click Submit
   - Full URL it will show: `https://www.foreverstillbeauty.com/sitemap.xml`
9. Go to **URL Inspection** → paste each page URL → click **"Request Indexing"** for each one:
   - `https://www.foreverstillbeauty.com/`
   - `https://www.foreverstillbeauty.com/about.html`
   - `https://www.foreverstillbeauty.com/album.html`
   - `https://www.foreverstillbeauty.com/method.html`
   - `https://www.foreverstillbeauty.com/beauty.html`
   - `https://www.foreverstillbeauty.com/contact.html`

That's it. Google will start crawling within hours.

---

## Step 2 — Google Business Profile

**N/A** — Forever Still Music is an online-only project with no physical location or service area. A Business Profile won't help and could confuse things. Skip this entirely.

---

## Step 3 — Bing Webmaster Tools

Takes 5 minutes if you've already done Google Search Console.

1. Go to **[bing.com/webmasters](https://www.bing.com/webmasters)**
2. Sign in with a Microsoft account (create one free if needed)
3. Click **"Import from Google Search Console"** — this is the fast path
4. Authorize the connection → Bing copies your property and sitemap automatically
5. Done.

---

## Step 4 — What to Expect (Realistic Timeline)

| Milestone | When |
|-----------|------|
| Google crawls your site | 24–72 hours after verification |
| Pages start appearing in search results | 1–2 weeks |
| Rankings begin stabilizing | 30–90 days |
| Meaningful organic traffic (if it's coming) | 3–6 months |

**Why the wait?** Google doesn't just index your site — it has to figure out what you're about, compare you to other sites, and decide where to rank you. With 34K+ plays and real content, you're starting with a real advantage. The timeline is normal for any new domain.

---

## Step 5 — What to Monitor Monthly

Check these once a month in Search Console. That's it.

**Worth watching:**
- **Total clicks** — is it growing over time?
- **Impressions** — are people seeing your pages in results?
- **Top queries** — what are people actually searching to find you?
- **Index Coverage** — any pages with errors? Fix them if so.

**Ignore completely:**
- Your own visits to your site
- Day-to-day ranking fluctuations (they're normal, they don't mean anything)
- Any tool that sends you weekly "SEO reports" via email — they're almost always trying to sell you something
- Domain Authority scores from third-party tools (Moz, Semrush) — not a Google metric, not meaningful for your stage

**One thing that actually helps more than anything:** Keep adding real content. Another song page. A blog post about the making of a track. A behind-the-scenes note. Fresh content with real words is what Google rewards long-term.

---

## Optional but worth doing

### Add your site to Apple / DuckDuckGo
Both use Bing's index, so completing Step 3 covers them automatically. No extra action needed.

### Pin your best review or quote on your Google result
Once you're indexed, you can add links in Search Console to pages you want highlighted. Hold off on this until you see how your pages rank naturally — usually 60+ days out.

---

*This checklist was generated as part of the SEO build completed May 2026.*
