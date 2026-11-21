# LinkedIn Strategy: 12-Week Plan

**Who this is for:** an ML / GenAI engineer at a data & AI platform company, already active on LinkedIn (5k+ followers), who wants the next 6 months of LinkedIn to build an audience for a side venture.

**Built from:**
- **Lara Acosta's 4-3-2-1 framework** and her **reintroduction post** formula (from the two Instagram reels). This is the operating system for the plan.
- The [sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills) playbook: 20 hook formulas, 2026 algorithm heuristics, comment strategy, and the skills that do the drafting. This is the execution layer.

Where the two disagree, the plan follows the 2026 reach data and says why (§10).

> `[fill]` marks a spot only you can complete. Never post a number you can't back up. The skills enforce this too: they won't invent a figure.

**Current as of: 21 November 2026.** Re-check §A (LinkedIn) and §B (AI and agents) each quarter; both change fast.

---

## A. What's true on LinkedIn right now (Nov 2026)

These are the platform changes this plan is built around. Most come from third-party trackers, not LinkedIn's own changelog, so each one carries a confidence note.

| When | Change | What it means for you | Confidence |
|---|---|---|---|
| **9 Nov 2026** | LinkedIn Engineering described **Profile Relevance**: an LLM-based system that recommends posts to people *outside* your network by matching post content to member profiles. Ranking works as retrieval first, then engagement. | **Say who the post is for and what problem it solves in the first 2 lines** ("If you run LLM evals in production…"). Keep your headline, About and posts on the same 2-3 topics, so the system knows who to show you to. Topic consistency now drives reach to non-followers. | High (LinkedIn engineering post) |
| **Oct 2026** | **Pinned comments**: authors can pin one comment to the top of their post. | Put the lead magnet or newsletter link in a **pinned** comment, instead of hoping your first comment stays on top. Or pin the best reader question to keep the thread going. | High |
| **Late Jul 2026 →** | **"Comment KEYWORD to get the guide" posts collapsed.** MagicPost's Oct 2026 analysis: these posts went from beating their author's usual views to about **half** of them. Follows the Mar 2026 authenticity update and the Jul 2026 "AI slop" report button. | **No keyword gates at all.** The earlier "once a month" allowance is removed. | Medium-high (vendor data, consistent with LinkedIn's own statements) |
| **2026 (rolling)** | **Format reach** (AuthoredUp, 3M posts): documents/carousels **1.39x** average reach, images **1.20x**, video **0.86x**, plain text below average. Video views fell ~36% YoY (Socialinsider). Carousels now accept mixed photos and videos you can reorder. | Carousels stay the main Educate format. **Real photos now beat plain text**, so add an image to Storytell posts. Don't build the strategy on video yet. | Medium (large analytics-tool datasets) |
| **2026** | **Analytics** now show **saves, sends, and in-network vs out-of-network reach**. Newsletters show email **sends and open rate**, and can have a video cover. | Track **sends** (people forwarding your post) and **out-of-network reach** (Profile Relevance working) weekly. Track newsletter open rate. | High |
| **Rolling out** | **Collaborative Posts** (co-authored with another member). | Co-author 1 post a month with a peer from your Audience A list. You both get each other's network. | Medium (not on every account yet) |
| **Contested** | **External-link penalty.** Some blogs claim about -60% reach. LinkedIn's VP of Content Daniel Roth reportedly said "we don't have anything in the algo about links." | Default to the pinned-comment link (no downside). Test one in-body link post in week 3 and compare. | Low: disputed |
| **Contested** | Claims that a "150B-parameter 360Brew" model ranks the whole feed. | Ignore the specifics. The confirmed part is Profile Relevance (above). | Low |
| **Unverified** | **Super Likes** showing on some accounts. | Watch, don't plan around it. | Low |

**Still holds in Nov 2026** (from the linkedin-skills Sep 2026 audit, updated by the repo through 18 Nov 2026):
- Line 1 is a number or statement, never a question (-34% median likes).
- No autopilot AI phrasing ("Here's what nobody tells you", "The result?").
- Most of a post's reach is decided in the first 60-90 minutes.
- 0-2 hashtags.

### Ideas this plan deliberately leaves out (outdated in 2026)
- Keyword comment gates ("comment GUIDE"). They lost about half their reach after Jul 2026.
- Engagement pods and like-for-like groups (detected and penalised).
- Hashtag stacking (5+ tags reads as spam; relevance now comes from the text).
- Posting about everything to "grow faster". Profile Relevance rewards a narrow, consistent topic.
- Video-first growth (video reach and views are down year on year).
- Bare text-only posts for personal stories (images now outperform them).
- Plain "link in first comment" (use a **pinned** comment).

---

## 0. The one-line strategy

**Be the engineer who shows what AI agents in production really cost, break and take, as of now, not as of 2024. Turn that trust into an owned audience (a newsletter + a lead magnet) that the side venture launches into.**

### The operating framework: 4-3-2-1

| | Rule | What it means for you |
|---|---|---|
| **4** | posts a week | Tue / Wed / Thu / Fri. Monday is commenting day. |
| **3** | content themes | **Educate** (production AI agents expertise) · **Storytell** (your path, building in public) · **Sell** (newsletter, lead magnet, venture) |
| **2** | types of audience | **Practitioners** who follow, share and amplify · **Buyers** who would pay for the venture (§3) |
| **1** | lead magnet | One flagship free asset that turns followers into subscribers (§4) |

Why this works for you:
- In late 2026 nobody needs another "what is an agent" post. Agents are everywhere (90% of developers use coding agents weekly, per JetBrains), but most enterprise agents still don't reach production or can't prove impact. People who show the *production* side with receipts are rare. You see real enterprise workloads every week, which is your unfair advantage.
- At 5k+ followers, original takes with evidence, a newsletter and a lead magnet are what compound.
- A side venture needs an audience you own before launch day. Followers are rented. Subscribers and lead-magnet sign-ups are owned.

---

## B. What's true in AI and agents right now (Nov 2026)

Your content has to sound like November 2026, not 2024. This is the landscape the Educate theme is built on. Each figure is "as reported", so check the original before you quote a number in a post.

| Area | Where things are (Nov 2026) | Your angle |
|---|---|---|
| **Adoption vs. production** | Most enterprises say they've deployed agents: 79% (Genpact), with other surveys between 54% and 72%. A widely cited Forrester/Anaconda figure says 88% of agent pilots never reach production, and most companies can't measure business impact. | The pilot-to-production gap is *the* topic. You live on the production side of it. |
| **Autonomy** | Only about 12% of production agents run fully autonomously. The dominant pattern is supervised autonomy (human-in-the-loop, risk tiers by data sensitivity and autonomy). | How to design autonomy tiers and approval points that don't kill the ROI. |
| **Evals → runtime guardrails** | Evals have moved from pre-launch test suites to runtime verification layers that check intermediate steps before the agent acts. | "Your eval suite should run in production, not just CI." |
| **Observability** | Trace-first observability is the H2 2026 infrastructure spend. Teams without it report about 3x more incidents (survey claim). CrowdStrike is buying Fiddler AI + Dreadnode (~$495M). | Teardowns of real agent traces (anonymised): where it actually broke. |
| **Agent FinOps** | Token spend from long-running agents is the new cloud bill. Budget caps per user/group and AI gateways are now standard platform features. | Cost per *resolved task*, not per token. Your strongest number-first hook. |
| **Context engineering + memory** | "Context rot": accuracy drops as long-running agents pile up context. The answer is context engineering: load, fetch just-in-time, compact, hand off to sub-agents, with short- and long-term memory layers. RAG is now one layer inside this stack, not the architecture. | Retire "RAG explained" content. Talk context budgets, compaction and memory design. |
| **Interop standards** | **MCP + A2A both live under the Linux Foundation's Agentic AI Foundation** (A2A joined 17 Aug 2026; A2A v1.0 shipped Mar 2026). AAIF also hosts AGENTS.md and goose, and has 250+ member orgs. Draft "AI Catalog" format for listing a domain's MCP servers and agent cards. | The protocol war is over. The open questions are trust, auth and permissions between agents. |
| **Agent security** | GAO report (20 Nov 2026): autonomous agents are already running cyberattacks with minimal human input, and there's no agreed way to certify defensive AI tools. | Tool permissions, prompt-injection and MCP-server hygiene for builders. Timely this month. |
| **Coding agents** | 90% of professional developers use coding agents weekly, 68% daily (JetBrains, 15k devs, Jul 2026). Claude Code is used by 39% at work, up from 18% in January. Only about 29% trust the output. Parallel agents are rising; review is the bottleneck. | How an ML engineer actually runs coding agents: what you delegate, what you review, what you never hand over. |
| **Model churn** | Several frontier and open-weight releases every month in Oct-Nov 2026 (Gemini 4 variants, GPT-6.x, very large open-weight models with 1M-token context). Names and dates differ between sources. | Don't do model hot takes. Show **how fast you can re-evaluate and swap a model** ("new model dropped Tuesday; here's our 48-hour eval"). |
| **Data platforms** | Platforms are pitching the lakehouse as the agent "control plane": agent builders, transactional DBs for agent memory, AI gateways, governance (all major summit themes in 2026). | Your employer's space. Post from the *practitioner* angle only, after policy check, never roadmap. |
| **India** | IndiaAI Mission has backed ~20 sovereign model efforts (Sarvam, Gnani.ai, BharatGen and others); 3 new indigenous foundation models were reported on 4 Nov 2026. | Indic-language and voice agents in production: a local angle few global creators can cover. |
| **Regulation** | EU AI Act: a provisional May 2026 omnibus deal moves high-risk obligations to Dec 2027 / Aug 2028. Watermarking obligations reportedly land Dec 2026. Final adoption status unconfirmed. | One explainer for Audience B (buyers). Don't present dates as settled. |

### Outdated AI topics to avoid
- "What is RAG / what is an agent / what is MCP" explainers. Your audience uses all three daily.
- Prompt-engineering tip lists. These have been replaced by context engineering.
- "Fine-tune vs. RAG" as a binary. In 2026 the answer is a context stack plus evals.
- "AI will replace developers" takes. 90% already use agents; the real conversation is review and trust.
- Leaderboard or "model X beats model Y" hot takes. They're stale in a week.
- "Chatbot" framing for enterprise use cases. Agents act; they don't just chat.
- "Agents are hype". Adoption is real; the honest story is the production and impact gap.

### Keep it current every week
- **Sunday, 20 min:** skim the week's agent news (e.g. AAIF/MCP/A2A updates, major model releases, LinkedIn Engineering, a daily agents news brief). Pick **at most one** item to react to.
- **Newsjacking rule:** reply to big news within 24-48 hours, only with a practitioner angle you can back up ("I ran it on our eval set: [number]"). It takes the week's Thursday Educate slot, so you stay at 4 posts.
- Re-check this section (§B) every quarter.

---

## 1. Guardrails first (do this before week 1)

1. **Read your employer's social media and outside-activities policy.** Confirm the side venture is disclosed and approved, and that it doesn't compete with your employer. This matters more now that 1 post in 4 is a "Sell" post.
2. **Never post customer names, customer numbers or internal roadmap.** Anonymise everything: "a Fortune 500 retailer", "a fintech team of 12". Receipts come from your own experiments, public benchmarks, or anonymised patterns.
3. Put "Views my own" in the About section, not the headline.
4. Keep the Story Bank (§7) **out of git**. It's already in this repo's `.gitignore`.

---

## 2. Profile upgrade (week 0, ~2 hours)

Use the **`linkedin-profile-optimizer`** skill. Paste your current headline, About and Featured sections and ask: *"Optimize my profile so people shipping AI agents follow me and download my lead magnet."*

**Headline options** (formula: What you do | Who you help | Result, ≤220 chars):

- `Shipping AI agents to production at [Employer] | Evals, observability & agent cost | Writing what actually breaks → [newsletter name]`
- `ML/GenAI Engineer @ [Employer] | Helping teams take AI agents from pilot to production | Free: [lead magnet name]`
- `I help engineering teams ship reliable AI agents | GenAI @ [Employer] | Building [venture name] on the side`

Pick the third only once the venture is public and approved.

**About section:** hook line with a real number from your work. Then 3 short paragraphs: what you build, the pattern you keep seeing, and what readers get by following. End with one CTA to the lead magnet. Keyword targets (5+ improves search impressions about 3x): `AI agents`, `agentic AI`, `GenAI`, `LLM evaluation`, `agent observability`, `context engineering`, `MCP`, `[Employer]`, `[Employer platform keywords]`.

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
| **Sell** | 1 | 25% | **Soft** sells only: lead magnet, newsletter issue, waitlist, later the launch. Each one teaches something on its own, and the ask comes last. | Single image or carousel + CTA in pinned comment | F8 Paid-vs-Free, F13 Bait-and-Switch, F1 Anaphora |

The skills playbook caps product posts at 1 per week. 4-3-2-1 lands exactly there, so the two agree. Keep Sell posts soft. A hard pitch every Friday trains people to scroll past.

**Topic territory for Educate, Nov 2026** (pick the ones you have receipts for; see §B for context):
- **Cost per resolved task**, not per token: what a production agent actually costs, line by line.
- **Pilot → production:** why most agent pilots stall, and the 3-4 things the ones that ship do differently.
- **Runtime evals:** verification layers between agent steps; LLM-as-judge calibration; regression evals when you swap models.
- **Agent traces:** anonymised teardowns of where a real agent run went wrong.
- **Context engineering and memory:** context rot, compaction, sub-agent handoff, what goes in long-term memory.
- **Autonomy tiers:** where humans approve, and how to keep that from killing the ROI.
- **Agent security:** tool permissions, prompt injection, MCP-server hygiene, agent identity under A2A.
- **Model swaps in 48 hours:** how you re-evaluate when a new model drops (instead of hot takes).
- **Coding agents for ML work:** what you delegate, what you review, what never gets handed over.
- **Indic-language and voice agents** (India angle), and **EU AI Act explainer** for buyers (once).

### 2 audiences

Write every post for **one** of these, and say in the plan which one it's for.

| Audience | Who | What they want | Which themes reach them |
|---|---|---|---|
| **A. Practitioners** | ML/GenAI/data engineers, DevRels, AI builders, mostly 1-20k followers | Tactics, code-level detail, honest failure stories | Educate (deep), Storytell |
| **B. Buyers** | The people who'd pay for the venture: `[fill]` (e.g. eng managers, heads of data/AI, founders moving agents from pilot to production) | Cost, risk, time-to-production, proof it works | Educate (cost/risk framing), Sell |

Audience A gives you reach and credibility. Audience B gives you revenue. Most weeks: 2 posts for A, 2 for B. Your comment lists (§5) mirror this split.

---

## 4. The 1 lead magnet

**Recommendation:** *The Agent Production Readiness Checklist (Nov 2026 edition)*. A one-page PDF plus a GitHub version of the checks you'd want before an agent ships: runtime evals and step verification, tracing, cost per task with budget caps, autonomy tier and approval points, tool/MCP permissions and prompt-injection tests, context and memory limits, model-swap regression suite, rollback. Date it, and update it each quarter. "Nov 2026 edition" signals that it's current, and every new edition is another Sell post. It shows your expertise directly, it's useful to both audiences, and it fits whatever the venture turns out to be.

Alternatives, if they fit the venture better: an open-source agent eval harness template, an agent cost-per-task calculator, or a 5-day email course on taking agents from pilot to production.

**How to distribute it (adapted for 2026, see §10):**
- Launch it with an **F8 Paid-vs-Free** post: "the checklist I'd charge for, free".
- Put the link in a **pinned comment** (new in Oct 2026), not the body. The link penalty is disputed (§A), but the pinned comment costs nothing and stays at the top.
- Open the launch post with who it's for ("If you're moving an agent from pilot to production this quarter…") so Profile Relevance can find Audience B outside your network.
- Collect emails on a simple landing page (Beehiiv, ConvertKit or Substack). That is the owned list.
- **No "comment CHECKLIST to get it" gates, ever.** Since late July 2026 these posts get about half their author's usual views (§A).
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
| Tue | Educate | A | Carousel (7 slides) | F7 Odd-Precision | "What one production agent actually costs per resolved task: $[fill], broken down line by line (model, tools, retries, human review)" | Saves |
| Wed | **Storytell** | A+B | Long text + 1 real photo | **Reintroduction post** | Four-part story (above) | Comments, follows |
| Thu | Educate | B | Poll | Poll | "What's actually blocking your agents from production? Evals / Observability / Cost / Security & permissions" | Reach + research for the lead magnet |
| Fri | Sell (soft) | A+B | Short text | F13 Bait-and-Switch | "Starting a weekly newsletter: [name]. One production agent teardown a week. First issue Sunday." Link in pinned comment. | Subs |

### Week 2: "Lead magnet launch"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | B | Long text | F10 Contrarian + Historical | "88% of agent pilots never reach production (Forrester/Anaconda, as reported). It isn't the model. It's where every data project since 2010 stalled: [fill]." Use week 1's poll results as a second receipt. | Comments |
| Wed | Storytell | A | Multi-image (3-4 photos) | F11 Emotional Cold-Open | A real moment: a customer workshop, a failed demo, a 2 AM incident. Dated and specific. | Likes |
| Thu | Educate | A | Carousel | F15 Explain-to-Kids | "Context rot explained like you're 10: why long-running agents get worse the longer they run", first of a series | Saves |
| Fri | **Sell** | B | Carousel preview + pinned-comment link | F8 Paid-vs-Free | **Lead magnet launch:** "The [N]-point Agent Production Readiness Checklist, Nov 2026 edition. I'd charge for it; it's free." Show 3 items, link to the rest. | Sign-ups |
| Sun | Newsletter #1 | — | — | — | Deep version of Tuesday's post | Subs |

### Week 3: "Depth + community"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | A | Long text | F19 Anecdote + Evidence | "I noticed [fill: how you review coding-agent output]. Then JetBrains' 2026 survey: 90% of devs use coding agents weekly, only ~29% trust the output." | Comments/Saves |
| Wed | Storytell | A | Text + tags | F14 Named Gratitude | Spotlight 3 builders or OSS maintainers whose work you use. Tag them and say why, specifically. | Reposts |
| Thu | Educate | A | Carousel | F15 Explain-to-Kids #2 | "MCP vs A2A explained like you're 10, and why both now live at the Linux Foundation" | Saves |
| Fri | Sell (soft) | B | Short text | F1 Anaphora (light) | Lead-magnet proof: "[N] people downloaded the checklist. The item most teams fail: [fill]." Link in pinned comment. | Sign-ups |
| Sun | Newsletter #2 | — | — | — | — | Subs |

### Week 4: "Build in public begins"
| Day | Theme | Aud. | Format | Formula | Angle | Goal |
|---|---|---|---|---|---|---|
| Tue | Educate | B | Long text | F17 Controlled A/B | "Same agent, two models (a closed frontier model vs an open-weight one), one variable changed. Cost per task and accuracy side by side: [fill]." | Comments |
| Wed | Storytell | A+B | Long text | F4 Time-Anchor (real, dated) | "On [date] I started building [venture] nights and weekends. [Real number]." Only once the venture is approved. | Comments |
| Thu | Educate | B | Poll | Poll | Validate a venture assumption: "Would you pay for X / Y / Z / none?" | Insight |
| Fri | Sell (soft) | B | Single image | F13 Bait-and-Switch | Waitlist teaser, or the newsletter's best issue so far | Waitlist/Subs |
| Sun | Newsletter #3 | — | — | — | Month-1 retro: what worked, with numbers | Subs |

**Weeks 5-12:** run **`linkedin-content-planner`** each Sunday with this brief: *"4 posts/week, themes Educate 50% / Storytell 25% / Sell 25%, audiences A and B, one lead magnet: [name]. Topics must reflect §B (Nov 2026 AI landscape); avoid the outdated-topic list."* It checks the mix, so no formula repeats and the goals stay balanced.

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
- **Links go in a pinned comment** ("Link pinned below ↓"), not the body.
- **Lines 1-2 name the audience and the problem.** Profile Relevance (Nov 2026) uses them to find readers outside your network.
- **Add a real photo to Storytell posts** and a carousel to most Educate posts. Plain text is now the weakest format for reach.
- **Co-author 1 post a month** using Collaborative Posts, once it's on your account.
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
| Saves per Educate post | Strongest signal (≈5x a like). Now shown in native analytics. | Rising trend |
| **Sends per post** | People forwarding your post in DMs. New in 2026 analytics. | Rising trend |
| **Out-of-network reach %** | Shows Profile Relevance is finding you new readers. New in 2026 analytics. | Rising trend |
| Newsletter open rate | Whether subscribers actually read it. New in 2026 analytics. | ≥ 40% |
| Comments >10 words | Quality engagement | ≥ 15 per post |
| Sell-post conversion | Sign-ups per Sell post, from the landing page | Rising trend |
| Audience mix (A vs B) of engagers | Are buyers showing up? Use `linkedin-engager-analytics`. | B ≥ 25% |
| Profile views | Comment engine working | +50% vs baseline |
| Inbound DMs from Audience B | Real demand signal | 1 per 5-8 posts (benchmark at 5-20k followers) |

**Review rule:** after 4 weeks, double down on the 2 formulas and 1 format with the best saves + comments, and the Sell angle with the best conversion. Drop the worst one.

---

## 9. Months 2-6 roadmap

- **Month 2:** Newsletter weekly. Start one signature recurring Educate series (e.g. "Agent Teardown #N": one real, anonymised agent trace a week). Guest on 1 podcast or Space.
- **Month 3:** Refresh or add a second lead magnet aimed squarely at Audience B (e.g. the agent cost-per-task calculator). Consider a free live session or masterclass, as Lara does, but promote it with a pinned-comment link rather than a keyword gate.
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
| **1 lead magnet** | §4: Agent Production Readiness Checklist (Nov 2026 edition), launched week 2 and pinned in Featured | **Keep.** Moved earlier than the original plan (week 2 instead of month 3). |
| **Reintroduction post** (relatable hook → timeline → feel-good close) | §6: week 1 Wednesday, then pinned | **Keep.** Ideal for an active account changing direction. Hook stays number-first, never a question. |
| **"Comment EVENT to join my masterclass"** CTA | §4 and §9 | **Drop the gate, keep the event.** Since late July 2026, "comment KEYWORD" posts get about half their author's usual views (MagicPost, Oct 2026). Use a pinned-comment link instead. |

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

---

## Sources for §A (checked 21 Nov 2026)

- [LinkedIn Product Updates: November 2026 Recap (Influent)](https://influent.co/blog/linkedin-updates-november-2026): Profile Relevance, Collaborative Posts, Super Likes
- [LinkedIn Algorithm and Platform Updates in 2026 (Influent)](https://influent.co/blog/linkedin-platform-updates): pinned comments
- [LinkedIn Algorithm Changes 2026: Every Update, Dated (VoiceMoat)](https://voicemoat.com/blog/linkedin-algorithm-changes-2026)
- [In-Ear Insights: LinkedIn Algorithm Updates October 2026 (Trust Insights)](https://www.trustinsights.ai/blog/2026/09/in-ear-insights-linkedin-algorithm-updates-october-2026/): retrieval-then-ranking
- [The 2026 LinkedIn Algorithm: What Actually Works Right Now (River)](https://rivereditor.com/blogs/2026-linkedin-algorithm-what-works-300-posts-tested)
- [How Does the LinkedIn Algorithm Work in 2026? (Flypost)](https://www.flypost.io/learn/linkedin-algorithm-study-data): link-penalty dispute
- [Best Performing Content on LinkedIn in 2026 (AuthoredUp)](https://authoredup.com/blog/best-performing-content-on-linkedin): format reach multipliers
- [Best Content Format on Social Platforms in 2026 (Buffer)](https://buffer.com/resources/data-best-content-format-social-media/)
- [13 New LinkedIn Features & Updates (SocialPilot)](https://www.socialpilot.co/blog/new-linkedin-features-and-updates): analytics, newsletters, carousels
- [sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills): Sep 2026 reach audit, v1.1.29 (18 Nov 2026)

Most of these are third-party summaries; the article pages couldn't be opened from this session, so the figures come from search-result extracts.

## Sources for §B (checked 21 Nov 2026)

- [Washington Times: GAO report on AI agents carrying out cyberattacks (20 Nov 2026)](https://washingtontimes.com/news/2026/nov/20/ai-agents-carrying-cyberattacks-minimal-human-input)
- AI Agents Directory news briefs: [6 Nov](https://aiagentsdirectory.com/news/ai-agents-news-brief-november-6-2026), [7 Nov](https://aiagentsdirectory.com/news/ai-agents-directory-daily-brief-november-7-2026), [18 Nov](https://aiagentsdirectory.com/news/ai-agents-news-brief-november-18-2026), [21 Nov](https://aiagentsdirectory.com/news/ai-agents-directory-daily-brief-november-21-2026): Genpact adoption figure, acquisitions
- [Agentic AI enterprise adoption 2026 (Agentic AI Institute)](https://agenticaiinstitute.org/agentic-ai-enterprise-adoption-2026-governance-gap/), [Enterprise AI agents mid-year 2026 (Aldric Research)](https://aldricresearch.com/enterprise-ai-agents-mid-year-2026), [AI agent observability/eval/governance market (Deepak Gupta)](https://guptadeepak.com/ai-agent-observability-evaluation-governance-the-2026-market-reality-check/), [Galileo: AI observability trends 2026](https://galileo.ai/blog/ai-observability-trends-2026)
- [Forbes: Agent2Agent joins the Agentic AI Foundation alongside MCP (19 Aug 2026)](https://www.forbes.com/sites/janakirammsv/2026/08/19/agent2agent-joins-the-agentic-ai-foundation-alongside-mcp/), [Tobira: what AAIF settles](https://blog.tobira.ai/a2a-mcp-agentic-ai-foundation/)
- [LangChain: context engineering for Deep Agents](https://langchain.com/blog/context-engineering-deep-agents-remember), [Oracle: what is context engineering](https://blogs.oracle.com/developers/what-is-context-engineering-the-four-operations-that-decide-whether-your-agent-survives-production)
- [JetBrains Research: AI coding agent adoption 2026](https://blog.jetbrains.com/research/2026/08/ai-coding-agent-adoption-2026/), [Stack Overflow: agents on a leash](https://stackoverflow.blog/2026/05/27/agents-on-a-leash-agentic-ai-remains-mostly-monitored-at-work/)
- [LLM Gateway: model release timeline](https://llmgateway.io/timeline), [Clone Systems: new AI models Nov 2026](https://www.clone-systems.com/blog/new-ai-models-november-2026-release-guide-and-security): names and dates conflict between sources
- [Atlan: Data + AI Summit 2026 announcements](https://atlan.com/know/ai-agent/databricks/databricks-data-ai-summit-2026-announcements/), [Bain: the lakehouse as agentic control plane](https://www.bain.com/insights/databricks-data-ai-summit-the-lakehouse-becomes-the-agentic-enterprise-control-plane/)
- [News On AIR: 3 indigenous AI foundation models under IndiaAI Mission (4 Nov 2026)](https://newsonair.gov.in/govt-launches-3-new-indigenous-ai-foundation-models-under-indiaai-mission-to-strengthen-homegrown-ai-capabilities/), [Kotak Neo: 20 sovereign models](https://www.kotakneo.com/news/sectors/india-ai-mission-20-indigenous-sovereign-models-sarvam-gnani-bharatgen-2026/)
- [Gibson Dunn: EU AI Act omnibus agreement](https://www.gibsondunn.com/eu-ai-act-omnibus-agreement-postponed-high-risk-deadlines-and-other-key-changes/), [Hogan Lovells: delay for high-risk AI rules](https://www.hoganlovells.com/en/publications/eu-legislators-agree-to-delay-for-highrisk-ai-rules)

Figures are as reported in search-result extracts, mostly from secondary sources; verify the primary source before quoting a number in a post.
