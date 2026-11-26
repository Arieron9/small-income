# Finding Leads Who Actually Answer

Target: **5%+ of contacted businesses reply** (and 1–2% buy).
150 emails → 0 replies is normal for generic cold email. The fix is **better leads + the right channel + something made for them.**

## Why 150 emails got 0 replies (most likely causes)

1. **Spam folder.** A new address sending many similar emails with links usually lands in spam. Test: send one to a Gmail and an Outlook account you own, and check mail-tester.com (free) for a score.
2. **Wrong channel.** A business **without a website usually doesn't read email.** They live on the phone, WhatsApp, Instagram and Facebook.
3. **Nothing made for them.** "Do you want a website?" is easy to ignore. "**Here is your website**" is not.
4. **Generic AI-sounding copy.** Owners spot it instantly.
5. **No follow-up.** Most replies come from the 2nd or 3rd touch, not the first.
6. **Weak leads.** Chains, closed businesses, businesses with 3 reviews, or people who already have a site.

---

## Step 1 — Score every lead (only contact 60+)

| Signal | Points |
|---|---|
| No website on Google (or only Facebook / Linktree / broken / not mobile) | **25** |
| 20–300 Google reviews (real customers, real money) | 15 |
| Rating 4.3+ (proud of their work → wants to show it) | 10 |
| Review in the last 30 days (still active) | 10 |
| **Owner replies to reviews** (engaged, reachable, cares about image) | **15** |
| Opened in the last 12 months / "new" business | **15** |
| Service where customers compare online: cleaning, landscaping, handyman, pressure washing, mobile detailing, movers, pet grooming, tutors, photographers, nail/lash/brow, barbers, food trucks, caterers | 10 |
| Owner-operated (owner's name in reviews: "Carlos was amazing") | 5 |
| Has a mobile number / WhatsApp / active Instagram | 5 |
| **Minus:** chain/franchise, 1–2 star average, no reviews in 6 months | −30 |

Score ≥ 60 → build a preview. Score 40–59 → message without a preview. < 40 → skip.

## Step 2 — Where the best leads are (ranked)

1. **Warm network — highest reply rate.** Israeli/Hebrew-speaking business owners in Miami (Aventura, North Miami Beach, Sunny Isles, Hollywood), FIU friends and their families, your two friends' businesses, community WhatsApp groups. Shared language = instant trust. Ask: "Who do you know with a business and no website?"
2. **New businesses.** They are actively buying everything right now. Google Maps listings with few but very recent reviews; new Florida LLC filings (Sunbiz, public); "grand opening" posts on Instagram/Facebook.
3. **Google Maps, scored as above.** Search "{{service}} near {{area}}" → open each result → check for the website button.
4. **People asking for help (inbound).** Local Facebook groups, Nextdoor, Reddit (r/smallbusiness, r/Miami), Craigslist gigs: search "need a website", "looking for web designer", "recommend someone to build a website". Reply helpfully with a free preview offer.
5. **Referral partners.** Accountants, print shops, business-formation services and insurance agents meet new businesses every week. Offer them $50 for every client they send.

## Step 3 — Channel order (not email first)

| Order | Channel | Why |
|---|---|---|
| 1 | **Phone call** (owner-operated businesses answer) | Highest reply rate by far. 20 seconds, then ask permission to text the link. |
| 2 | **Instagram / Facebook DM** with the preview link | Where these owners actually are. |
| 3 | **WhatsApp** (Israel, or if they list it) | Normal for businesses in Israel; only message business numbers they publish, one message + one follow-up. |
| 4 | Email | Only if the business clearly uses it; personal, one at a time, never bulk. |

**Don't** blast automated texts to US numbers — US law (TCPA) restricts automated texting without consent. Calling a business and *asking* "can I text you the link?" is the clean way.

### 20-second call script
> "Hi, is this the owner? My name's {{Name}}, I'm a student at FIU — quick one: I noticed {{Business}} has great reviews on Google but no website, so I actually built you one already, free to look at. Can I text you the link? … Great, if you like it, it's yours for $300; if not, no problem at all."

### עברית — שיחה קצרה
> "היי, מדבר עם הבעלים? אני {{שם}}, סטודנט — ראיתי שלעסק יש ביקורות מעולות בגוגל אבל אין אתר, אז בניתי לכם אחד, רק שתראו. אפשר לשלוח לכם קישור בוואטסאפ? … אם אהבתם — הוא שלכם ב־₪1,000. אם לא — בכלל לא נורא."

### Follow-up sequence (per lead)
Day 0 call/DM with link → Day 2 "did you get a chance to open it?" → Day 5 small improvement ("added your menu / your before-after photos") → Day 10 last message. Then stop.

## Realistic numbers per 100 scored leads (rough estimates, will update with your real data)

| | Calls + DMs with preview | Old way (bulk email) |
|---|---|---|
| Respond | 15–30 | 0–3 |
| Interested / look at site | 8–15 | 0–1 |
| Buy | 2–5 | 0 |

## Step 4 — The lead-research agent (prompt for your agent)

Give this to your research agent (any agent that can browse the web / Google Maps):

```
You are a lead researcher for a small web-design studio in Miami.
Find 20 local businesses in {{AREA}} in these categories: {{CATEGORIES}}.

For each business, check its Google Maps listing and record:
name, category, address, phone, Instagram/Facebook link, Google rating,
number of reviews, date of the most recent review, whether the owner replies
to reviews (yes/no), owner's first name if mentioned in reviews,
website status (none / facebook-only / linktree / broken / outdated / good),
and 2 short phrases customers repeat in reviews (e.g. "always on time").

Score each with this rubric:
+25 no real website, +15 20-300 reviews, +10 rating 4.3+,
+10 review in last 30 days, +15 owner replies to reviews,
+15 opened in last 12 months, +10 high-comparison service category,
+5 owner-operated, +5 mobile/WhatsApp/active Instagram;
-30 if chain/franchise, rating under 3, or no reviews in 6 months.

Skip anything with a good website. Only include real, verifiable businesses —
never guess a phone number or invent data; write "unknown" instead.
Output a CSV with the columns of leads.csv, sorted by score, highest first.
```

Then send me the top 5–10 → I build their preview sites → you call/DM.
