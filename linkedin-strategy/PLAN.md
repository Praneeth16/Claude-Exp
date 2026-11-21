# LinkedIn Strategy: 12-Week Plan

**Who this is for:** an ML / GenAI engineer at a data & AI platform company, already active on LinkedIn (5k+ followers), who wants the next 6 months of LinkedIn to build an audience for a side venture.

**Built from:**
- **Lara Acosta's 4-3-2-1 framework** and her **reintroduction post** formula (from the two Instagram reels). This is the operating system for the plan.
- The [sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills) playbook: 20 hook formulas, 2026 algorithm heuristics, comment strategy, and the skills that do the drafting. This is the execution layer.

Where the two disagree, the plan follows the 2026 reach data and says why (§10).

> `[fill]` marks a spot only you can complete. Never post a number you can't back up. The skills enforce this too: they won't invent a figure.

---

## 0. The one-line strategy

**Be the engineer who shows what GenAI in production really costs, breaks and takes. Turn that trust into an owned audience (a newsletter + a lead magnet) that the side venture launches into.**

### The operating framework: 4-3-2-1

| | Rule | What it means for you |
|---|---|---|
| **4** | posts a week | Tue / Wed / Thu / Fri. Monday is commenting day. |
| **3** | content themes | **Educate** (production GenAI expertise) · **Storytell** (your path, building in public) · **Sell** (newsletter, lead magnet, venture) |
| **2** | types of audience | **Practitioners** who follow, share and amplify · **Buyers** who would pay for the venture (§3) |
| **1** | lead magnet | One flagship free asset that turns followers into subscribers (§4) |

Why this works for you:
- Feeds are full of GenAI hype. People building it in production, with real receipts, are rare. You see real enterprise workloads every week, which is your unfair advantage.
- At 5k+ followers, original takes with evidence, a newsletter and a lead magnet are what compound.
- A side venture needs an audience you own before launch day. Followers are rented. Subscribers and lead-magnet sign-ups are owned.

---

## 1. Guardrails first (do this before week 1)

1. **Read your employer's social media and outside-activities policy.** Confirm the side venture is disclosed and approved, and that it doesn't compete with your employer. This matters more now that 1 post in 4 is a "Sell" post.
2. **Never post customer names, customer numbers or internal roadmap.** Anonymise everything: "a Fortune 500 retailer", "a fintech team of 12". Receipts come from your own experiments, public benchmarks, or anonymised patterns.
3. Put "Views my own" in the About section, not the headline.
4. Keep the Story Bank (§7) **out of git**. It's already in this repo's `.gitignore`.

---

## 2. Profile upgrade (week 0, ~2 hours)

Use the **`linkedin-profile-optimizer`** skill. Paste your current headline, About and Featured sections and ask: *"Optimize my profile so GenAI builders follow me and download my lead magnet."*

**Headline options** (formula: What you do | Who you help | Result, ≤220 chars):

- `Shipping GenAI to production at [Employer] | Agents, RAG & LLM evals | Writing what it actually costs and breaks → [newsletter name]`
- `ML/GenAI Engineer @ [Employer] | Helping teams take LLM apps from demo to production | Free: [lead magnet name]`
- `I help engineering teams ship reliable AI agents | GenAI @ [Employer] | Building [venture name] on the side`

Pick the third only once the venture is public and approved.

**About section:** hook line with a real number from your work. Then 3 short paragraphs: what you build, the pattern you keep seeing, and what readers get by following. End with one CTA to the lead magnet. Keyword targets (5+ improves search impressions about 3x): `GenAI`, `LLM`, `RAG`, `AI agents`, `MLOps`, `LLM evaluation`, `[Employer]`, `[Employer platform keywords]`.

**Featured section (3 slots):**
1. **The lead magnet** (top slot, always)
2. Newsletter subscribe link
3. Your reintroduction post (week 1), later swapped for the venture's waitlist page

**Banner:** one line of promise plus the lead magnet or newsletter name. No logo collage.

---

## 3. The 3 themes and the 2 audiences

### 3 themes

| Theme | Posts/week | Share | What it means for you | Formats | Best hook formulas (skills repo) |
|---|---|---|---|---|---|
| **Educate** | 2 | 50% | Teardowns, cost math, eval frameworks, architecture patterns, "what broke and why". Polls and creator spotlights live here too. | Carousel, long text, poll | F7 Odd-Precision, F10 Contrarian + Receipts, F15 Explain-to-Kids, F19 Anecdote + Evidence, F8 Paid-vs-Free |
| **Storytell** | 1 | 25% | Your path, mistakes, lessons from customer work (anonymised), building the venture in public | Long text, multi-image (3-4 real photos) | Reintroduction post (§6), F3 Year-over-Year, F11 Emotional Cold-Open, F4 Time-Anchor (dated and real only), F14 Named Gratitude |
| **Sell** | 1 | 25% | **Soft** sells only: lead magnet, newsletter issue, waitlist, later the launch. Each one teaches something on its own, and the ask comes last. | Single image or carousel + CTA in first comment | F8 Paid-vs-Free, F13 Bait-and-Switch, F1 Anaphora |

The skills playbook caps product posts at 1 per week. 4-3-2-1 lands exactly there, so the two agree. Keep Sell posts soft. A hard pitch every Friday trains people to scroll past.

**Topic territory for Educate** (pick the ones you have receipts for):
- Cost per outcome of an agent vs. cost per token. What teams actually pay.
- LLM-as-judge evals: where they lie and how to calibrate them.
- RAG failure modes: chunking, stale indexes, retrieval that looks right but isn't.
- "Demo → production" gap: governance, latency budgets, guardrails, monitoring.
- Fine-tune vs. prompt vs. RAG: when each wins, with numbers.
- Explain-to-kids series: tokens, embeddings, vector search, agents, MCP. (Strong save-driver.)
- Contrarian takes with history: "every data platform wave had this exact moment".

### 2 audiences

Write every post for **one** of these, and say in the plan which one it's for.

| Audience | Who | What they want | Which themes reach them |
|---|---|---|---|
| **A. Practitioners** | ML/GenAI/data engineers, DevRels, AI builders, mostly 1-20k followers | Tactics, code-level detail, honest failure stories | Educate (deep), Storytell |
| **B. Buyers** | The people who'd pay for the venture: `[fill]` (e.g. eng managers, heads of data/AI, founders shipping LLM features) | Cost, risk, time-to-production, proof it works | Educate (cost/risk framing), Sell |

Audience A gives you reach and credibility. Audience B gives you revenue. Most weeks: 2 posts for A, 2 for B. Your comment lists (§5) mirror this split.

---

## 4. The 1 lead magnet

**Recommendation:** *The Production GenAI Readiness Checklist*. A one-page PDF plus a Notion/GitHub version of the checks you'd want before an LLM app or agent ships: evals, cost ceilings, latency budgets, guardrails, monitoring, rollback. It shows your expertise directly, it's useful to both audiences, and it fits whatever the venture turns out to be.

Alternatives, if they fit the venture better: an open-source eval harness template, a "cost per outcome" calculator spreadsheet, or a 5-day email course.

**How to distribute it (adapted for 2026, see §10):**
- Launch it with an **F8 Paid-vs-Free** post: "the checklist I'd charge for, free".
- Put the link **in the first comment**, never in the body. In-body links cut reach 40-60%.
- Collect emails on a simple landing page (Beehiiv, ConvertKit or Substack). That is the owned list.
- **No "comment CHECKLIST to get it" gates.** LinkedIn's March 2026 authenticity update names these as engagement bait. If you want a keyword gate, use one at most once a month, and only with a real deliverable sent by hand.
- Pin it in Featured. Re-share it through the newsletter every month, and point to it in the P.S. of any Educate post on a related topic.

Build it in **week 0-1**, launch it in **week 2** (§6).

---

## 5. The comment engine (where most of the inbound comes from)

Comments drive 60-70% of inbound DMs. At 5k+, weight posting and commenting 1:1.

- **10-20 substantive comments per day** (paragraph-length, with a number or a counterpoint, never "Great post!").
- **Monday is commenting-only day:** 20+ comments, no post.
- **Mix:** 70% peers (similar follower count), 20% aspirational (10-100x your size), 10% prospects for the venture.
- **First 60 minutes:** comment on a target creator's post within its first hour.
- **Build three lists** (save them in a doc, turn on post notifications for each person):
  - *Peers (15):* Audience A, GenAI/ML engineers and DevRels at 3k-20k followers.
  - *Aspirational (8):* large AI and data voices whose audience you want.
  - *Prospects (7):* Audience B, the people the venture would serve.
- Use **`linkedin-comment-drafter`** on a post URL. Always edit the draft into your own words before posting.

**Own your first 90 minutes after posting:** reply to every comment with a real answer (different wording each time; templated replies get down-ranked). Use **`linkedin-reply-handler`** when a thread gets busy.

**Don't:** join engagement pods, use "comment YES for the PDF" gates, or send automated DMs. Each is a named 2026 penalty target.

---

## 6. 4-week launch calendar (4-3-2-1 applied)

Each week: 2 Educate · 1 Storytell · 1 Sell, with the audience marked as **A** (practitioners) or **B** (buyers). Angles are starting points. Fill `[fill]` from your own work, or run `linkedin-interviewer` first (§7) and let it fill them.

### The reintroduction post (week 1, Wednesday)

From Lara's reel: a four-part story post that tells your existing 5k+ followers who you are *now* and why they should keep reading. Use it once, at the start of the new direction, and pin it to Featured.

1. **Relatable hook.** A specific, slightly vulnerable line your audience recognises in themselves. Number-first if you can, never a question. e.g. *"[N] years ago I was [fill: a role/moment people relate to], and I had no idea what an embedding was."*
2. **Timeline.** 3-5 dated beats from then to now. Short lines, real dates, one number each. e.g. *"[Year]: [fill]. [Year]: [fill]. Today: shipping GenAI to production for [anonymised scale]."*
3. **What I do now and what you'll get here.** The pivot: what you'll post about (your 3 themes, in plain words) and who it's for (your 2 audiences).
4. **Feel-good close.** Warm and grateful, not salesy. Thank the people who followed the earlier version of you. End with a light, specific question, e.g. *"What's one thing you'd want to see torn down from a real GenAI system?"*

Run the draft through `linkedin-post-writer` (closest formulas: **F3 Year-over-Year Pivot** for the timeline, **F16 Status-Strip Humility** for the tone) and then `linkedin-humanizer --mode audit`.

> The summary named three of the four parts (hook, timeline, feel-good close). Part 3 is my reconstruction of the standard middle step. Swap in Lara's exact version if you have it.

### Week 1: "Reintroduce"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | A | Carousel (7 slides) | F7 Odd-Precision | "What a production RAG app actually costs per 1,000 queries: $[fill], broken down line by line" | Saves |
| Wed | **Storytell** | A+B | Long text | **Reintroduction post** | Four-part story (above) | Comments, follows |
| Thu | Educate | B | Poll | Poll | "What's actually blocking your GenAI app from production? Evals / Cost / Latency / Governance" | Reach + research for the lead magnet |
| Fri | Sell (soft) | A+B | Short text | F13 Bait-and-Switch | "Starting a weekly newsletter: [name]. One production GenAI teardown a week. First issue Sunday." Link in first comment. | Subs |

### Week 2: "Lead magnet launch"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | B | Long text | F10 Contrarian + Historical | "Most GenAI apps don't fail on the model. They fail where every data project since 2010 failed: [fill]." Use week 1's poll results as a receipt. | Comments |
| Wed | Storytell | A | Multi-image (3-4 photos) | F11 Emotional Cold-Open | A real moment: a customer workshop, a failed demo, a 2 AM incident. Dated and specific. | Likes |
| Thu | Educate | A | Carousel | F15 Explain-to-Kids | "AI agents explained like you're 10", first of a series | Saves |
| Fri | **Sell** | B | Carousel preview + link in 1st comment | F8 Paid-vs-Free | **Lead magnet launch:** "The [N]-point Production GenAI Readiness Checklist. I'd charge for it; it's free." Show 3 items, link to the rest. | Sign-ups |
| Sun | Newsletter #1 | — | — | — | Deep version of Tuesday's post | Subs |

### Week 3: "Depth + community"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | A | Long text | F19 Anecdote + Evidence | "I noticed [fill: pattern across N teams]. Then I checked [public benchmark/paper]." | Comments/Saves |
| Wed | Storytell | A | Text + tags | F14 Named Gratitude | Spotlight 3 builders or OSS maintainers whose work you use. Tag them and say why, specifically. | Reposts |
| Thu | Educate | A | Carousel | F15 Explain-to-Kids #2 | "RAG explained like you're 10" | Saves |
| Fri | Sell (soft) | B | Short text | F1 Anaphora (light) | Lead-magnet proof: "[N] people downloaded the checklist. The item most teams fail: [fill]." Link in first comment. | Sign-ups |
| Sun | Newsletter #2 | — | — | — | — | Subs |

### Week 4: "Build in public begins"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | B | Long text | F17 Controlled A/B | "Same agent, two setups, one variable changed: [fill]. Cost and accuracy side by side." | Comments |
| Wed | Storytell | A+B | Long text | F4 Time-Anchor (real, dated) | "On [date] I started building [venture] nights and weekends. [Real number]." Only once the venture is approved. | Comments |
| Thu | Educate | B | Poll | Poll | Validate a venture assumption: "Would you pay for X / Y / Z / none?" | Insight |
| Fri | Sell (soft) | B | Single image | F13 Bait-and-Switch | Waitlist teaser, or the newsletter's best issue so far | Waitlist/Subs |
| Sun | Newsletter #3 | — | — | — | Month-1 retro: what worked, with numbers | Subs |

**Weeks 5-12:** run **`linkedin-content-planner`** each Sunday with this brief: *"4 posts/week, themes Educate 50% / Storytell 25% / Sell 25%, audiences A and B, one lead magnet: [name]."* It checks the mix, so no formula repeats and the goals stay balanced.

---

## 7. Your skill workflow (sergebulaev/linkedin-skills)

**Install (Claude Code):**
```
/plugin marketplace add sergebulaev/linkedin-skills
/plugin install linkedin-skills@linkedin-skills
```
Or on claude.ai: Customize → Plugins → Add marketplace → `sergebulaev/linkedin-skills` → Discover → Add.

**One-time setup (week 0, ~1 hour):**
1. **`linkedin-interviewer --mode bank`**: 20-40 min interview. It builds your Story Bank of timeline, receipts, turning points and positions. The timeline section is the raw material for the reintroduction post. Do this first.
2. **`linkedin-humanizer --mode profile`**: paste 3-6 of your past posts. It learns your voice fingerprint.
3. **`linkedin-profile-optimizer`**: rewrite headline, About and Featured (§2).
4. **`linkedin-hook-extractor`**: feed it 5-10 viral posts from your aspirational list (Lara's included). Learn which formulas work in *your* niche.

**Weekly loop (~4 hours/week total):**

| When | Skill | What you do |
|---|---|---|
| Sun (30 min) | `linkedin-content-planner` | Plan the week with the 4-3-2-1 brief above + last week's data |
| Sun (2 hrs) | `linkedin-post-writer` | Batch-draft 4 posts. Pick the formula by goal. Tag each with theme + audience. |
| Before every post | `linkedin-humanizer --mode audit` | Scrub AI tells, check hook ≤140 chars on mobile, length, link placement |
| Mon + daily (20-30 min) | `linkedin-comment-drafter` | Draft 10-20 comments from your three lists. **Edit each one by hand.** |
| Post day, first 90 min | `linkedin-reply-handler` | Reply to every comment, no templates |
| Ongoing | `linkedin-thread-monitor` | Track threads you commented on for replies and DMs |
| Monthly | `linkedin-engager-analytics` | Check what share of engagers is Audience A vs B. Adjust the lists. |
| Newsletter day | `linkedin-repurposer` | Turn the week's best Educate post into the newsletter issue |

**Posting rules (the skills enforce these; keep them anyway):**
- Line 1 is a **number or statement, never a question** (-34% median likes). The question goes at the end.
- Hook fits in **140 characters** (mobile "…see more" cutoff).
- 900-1,300 characters by default. Long posts (1,500+) work if every line earns its place.
- **0-2 hashtags**, at the end.
- **No links in the body.** Put them in the first comment ("Link below ↓").
- One contrast and one triple per post at most. No "The result?" or "Here's what nobody tells you".
- Add a **P.S.** when there's a real follow-up (+7.5%). This is where the lead magnet gets mentioned on Educate posts.
- Every claim gets a specific (date, number, name) within 2 lines.
- Posting times: 8:00-9:00 AM IST Tue-Fri for an India-heavy audience. If most of your audience is in the US, use 6:30-8:30 PM IST. Re-check in analytics after 4 weeks.
- Never 2 posts in one day, never 6+ in a week, never the same formula twice in 7 days.

---

## 8. Metrics: what to track (Sunday, 15 min)

| Metric | Why | Week-12 target (set your own baseline in week 0) |
|---|---|---|
| **Lead magnet sign-ups + newsletter subscribers** | The owned list the venture launches into. This is the north star. | Baseline + [fill] |
| Saves per Educate post | Strongest signal (≈5x a like) | Rising trend |
| Comments >10 words | Quality engagement | ≥ 15 per post |
| Sell-post conversion | Sign-ups per Sell post, from the landing page | Rising trend |
| Audience mix (A vs B) of engagers | Are buyers showing up? Use `linkedin-engager-analytics`. | B ≥ 25% |
| Profile views | Comment engine working | +50% vs baseline |
| Inbound DMs from Audience B | Real demand signal | 1 per 5-8 posts (benchmark at 5-20k followers) |

**Review rule:** after 4 weeks, double down on the 2 formulas and 1 format with the best saves + comments, and the Sell angle with the best conversion. Drop the worst one.

---

## 9. Months 2-6 roadmap

- **Month 2:** Newsletter weekly. Start one signature recurring Educate series (e.g. "Production GenAI Teardown #N"). Guest on 1 podcast or Space.
- **Month 3:** Refresh or add a second lead magnet aimed squarely at Audience B (e.g. the cost-per-outcome calculator). Consider a free live session or masterclass, as Lara does, but promote it with a link in the first comment rather than a keyword gate.
- **Month 4:** Storytell slot becomes a weekly venture build-in-public update. Use polls to validate pricing and features.
- **Month 5:** Waitlist and soft launch to the email list first, LinkedIn second.
- **Month 6:** Launch week. Still one Sell post, plus a Storytell ("why I built this") and an Educate post (the problem, with data). Reuse the stories already tested in the Story Bank.

---

## 10. Instagram reel tactics: merged

Source: Lara Acosta (@laraacostar), two reels on LinkedIn content strategy. Built from the screenshots and summary you shared, not a full transcript.

| Reel tactic | Where it fits in this plan | Verdict |
|---|---|---|
| **4 posts a week** | §0 and §6: Tue-Fri, with Monday for comments | **Keep.** Inside the skills playbook's 3-5/week safe range. |
| **3 content themes: Educate, Storytell, Sell** | §3. These replace the skills repo's 4-pillar mix. Community content (polls, spotlights) folds into Educate and Storytell. | **Keep.** Sell is held to 1/week and kept soft, which matches the playbook's product-post cap. |
| **2 types of audience** | §3: Practitioners (A) and Buyers (B). Every post is tagged; comment lists mirror the split. | **Keep.** |
| **1 lead magnet** | §4: Production GenAI Readiness Checklist, launched week 2 and pinned in Featured | **Keep.** Moved earlier than the original plan (week 2 instead of month 3). |
| **Reintroduction post** (relatable hook → timeline → feel-good close) | §6: week 1 Wednesday, then pinned | **Keep.** Ideal for an active account changing direction. Hook stays number-first, never a question. |
| **"Comment EVENT to join my masterclass"** CTA | §4 and §9 | **Adapt.** LinkedIn's March 2026 authenticity update targets comment-gate CTAs, and posts flagged as "AI slop" lose about 40% of views. Use a link in the first comment instead; at most one real, hand-delivered keyword gate a month. |

---

## Week-0 checklist

- [ ] Read your employer's social media / outside-activity policy. Disclose the venture.
- [ ] Install linkedin-skills.
- [ ] Run `linkedin-interviewer` (Story Bank, especially the timeline for the reintroduction post).
- [ ] Run `linkedin-humanizer --mode profile` (voice).
- [ ] Define Audience B in one sentence (who pays for the venture).
- [ ] Build the lead magnet + landing page.
- [ ] Rewrite headline, About, Featured, banner.
- [ ] Create the newsletter (name + description).
- [ ] Build the three comment lists (peers / aspirational / prospects).
- [ ] Record baseline metrics.
- [ ] Draft the reintroduction post and the rest of week 1.
