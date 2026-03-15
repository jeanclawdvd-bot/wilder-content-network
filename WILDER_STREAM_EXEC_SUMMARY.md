# WILDER STREAM — Executive Summary

### The Decentralized Content Engine for Wilder World
**Date:** March 15, 2026
**Author:** Frank Wilder, CEO — Wilder World
**Status:** DRAFT — Pending Team Sign-Off

---

## 1. VISION

Wilder World builds a self-sustaining content flywheel where **players create the source content, clippers distribute it globally, and $WILD token powers the entire economy.** Zero internal content production cost. Infinite output.

The system has two sides:

| | **WILDER STREAM** | **WILDER CLIPS** |
|---|---|---|
| **Who** | Players who stream/record WW gameplay | Editors who clip & distribute short-form content |
| **What they do** | Upload high-quality gameplay footage | Turn raw footage into viral TikTok/Reels/Shorts |
| **How they earn** | $WILD based on Stream Quality Score | $WILD based on views their clips generate |
| **Our cost** | $WILD tokens | $WILD tokens |
| **Our benefit** | Infinite raw content library | Infinite organic reach across all platforms |

**The flywheel:** More streamers → more raw content → more clippers → more distribution → more players discover WW → more streamers.

---

## 2. WILDER STREAM — The Source Engine

### 2.1 What It Is

A proprietary web app (**stream.wilderworld.com**) where Wilder World players upload their gameplay recordings and livestream VODs. Think of it as Wilder World's own content depot — a library of high-quality gameplay footage that feeds the entire marketing machine.

### 2.2 Who It's For

- Players who already stream WW on Twitch, YouTube, Kick
- Players who record gameplay but don't have a streaming audience
- Content creators looking for a new revenue stream
- Anyone playing WW who wants to earn while they play

### 2.3 The Upload Flow

```
Player records/streams WW gameplay
        ↓
Uploads to Wilder Stream (drag & drop, or connect Twitch/YT for auto-import)
        ↓
System auto-analyzes: resolution, duration, gameplay quality, kill count
        ↓
Stream Quality Score (SQS) calculated
        ↓
$WILD payout based on SQS
        ↓
Footage enters the Content Library (available for clippers)
```

### 2.4 Stream Quality Score (SQS)

The payout formula incentivizes exactly the content we want: **long, high-resolution, action-packed gameplay.**

```
SQS = Base Rate × Resolution Multiplier × Duration Multiplier × Action Density × Concurrent Viewers Bonus
```

#### Resolution Multiplier
| Resolution | Multiplier | Why |
|---|---|---|
| 1080p | 1.0× | Minimum accepted |
| 1440p (2K) | 1.5× | Our preferred sweet spot |
| 2160p (4K) | 2.5× | Premium — best for cropping to 9:16 |
| 4K + HDR | 3.0× | Top tier — future-proofed content |

#### Duration Multiplier
| Duration | Multiplier | Why |
|---|---|---|
| 10–30 min | 1.0× | Short session |
| 30–60 min | 1.3× | Standard stream |
| 1–2 hrs | 1.6× | Solid session, more clip-worthy moments |
| 2–4 hrs | 2.0× | Marathon — maximum content value |
| 4+ hrs | 2.0× (cap) | Diminishing returns after 4hrs |

#### Action Density Score
AI-analyzed metric based on:
- **Kill count** per hour of footage
- **Kill streaks** (multi-kills, sprees)
- **Combat engagement rate** (% of time in active combat vs. idle/walking)
- **Cinematic moments** (vehicle sequences, aerial views, explosions, boss fights)

| Action Density | Multiplier |
|---|---|
| Low (mostly idle/exploring) | 0.5× |
| Medium (regular gameplay) | 1.0× |
| High (frequent kills, constant action) | 1.5× |
| Highlight Reel (non-stop combat, streaks) | 2.0× |

#### Concurrent Viewers Bonus (For Livestreamers)
If the player was livestreaming while recording, their average concurrent viewers during the session provide a bonus. This rewards streamers who are already distributing WW content to an audience — and the bigger their audience, the more organic reach WW gets for free.

| Avg. Concurrent Viewers | Bonus |
|---|---|
| 0 (recorded, not streamed) | 1.0× (no bonus) |
| 1–50 | 1.2× |
| 50–500 | 1.5× |
| 500–5,000 | 2.5× |
| 5,000+ | 4.0× |

#### Payout Calibration

**Target: USD-pegged rates that beat organic Twitch earnings.**

Market context for a 1K CCV streamer, 1-hour stream:
- Organic Twitch earnings: ~$25–50/hr (ads + bits + subs)
- Sponsored stream rate: ~$1,000–1,500/hr (brand deal)
- **Wilder Stream target: $50–100/hr equivalent in $WILD** (doubles organic income without hitting sponsor rates)

```
Base Rate = $5 USD equivalent in $WILD per 1.0 SQS
(Adjusted monthly based on $WILD spot price)
```

At current $WILD ≈ $0.022, Base Rate = ~227 WILD per 1.0 SQS.

#### Example Payouts

| Scenario | SQS Calc | SQS | $WILD | USD Equiv. |
|---|---|---|---|---|
| Casual player, 1080p, 20min, low action, no stream | 1.0 × 1.0 × 0.5 × 1.0 | 0.5 | ~114 | ~$2.50 |
| Decent session, 2K, 1hr, medium action, no stream | 1.5 × 1.3 × 1.0 × 1.0 | 1.95 | ~443 | ~$9.75 |
| Good session, 4K, 1hr, high action, 200 CCV | 2.5 × 1.3 × 1.5 × 1.5 | 7.31 | ~1,659 | ~$36.50 |
| Strong streamer, 4K, 2hrs, high action, 1K CCV | 2.5 × 2.0 × 1.5 × 2.5 | 18.75 | ~4,256 | ~$93.63 |
| Top streamer, 4K HDR, 3hrs, highlight reel, 3K CCV | 3.0 × 2.0 × 2.0 × 2.5 | 30.0 | ~6,810 | ~$149.82 |
| Elite streamer, 4K HDR, 4hrs, highlight reel, 10K CCV | 3.0 × 2.0 × 2.0 × 4.0 | 48.0 | ~10,896 | ~$239.71 |

**Sanity check — 1K CCV streamer, 1hr, 4K, high action:**
- Earns ~$94 from Wilder Stream upload
- Plus organic Twitch revenue (~$25-50/hr) they're already earning
- Total: ~$120-145/hr — compelling enough to stream WW over other games
- Plus 5% royalty on downstream clips (could add $20-100+ if clips go viral)

*All USD equivalents auto-adjust monthly. If $WILD rises to $0.10, fewer tokens distributed for same USD value. If $WILD drops, more tokens. Treasury exposure is managed, not open-ended.*

### 2.5 Content Guidelines

To be accepted into Wilder Stream, footage must:
- ✅ Be authentic Wilder World gameplay (AI-verified)
- ✅ Minimum 1080p resolution, 30fps
- ✅ Minimum 10 minutes duration
- ✅ No watermarks from other platforms
- ✅ No hate speech, slurs, or offensive overlays
- ❌ Re-uploads of other players' content = permanent ban
- ❌ AI-generated or synthetic gameplay = rejected

### 2.6 Streamer Tiers

Consistent uploaders unlock higher base rates and perks:

| Tier | Requirement | Perk |
|---|---|---|
| **Rookie** | First upload | Standard rates |
| **Regular** | 10+ uploads, 20+ hrs total | +10% base rate |
| **Veteran** | 50+ uploads, 100+ hrs, avg SQS > 3.0 | +25% base rate, early access to new maps |
| **Elite** | 200+ uploads, top 10 monthly SQS | +50% base rate, featured streamer badge, WW merch |
| **Partner** | By invitation | Custom rate, co-marketing, official WW streamer title |

---

## 3. WILDER CLIPS — The Distribution Engine

### 3.1 What It Is

A Vyro-style clipping marketplace (**clips.wilderworld.com**) where editors browse the Wilder Stream content library, create short-form clips, distribute them on social platforms, and earn $WILD based on views.

### 3.2 Who It's For

- Short-form video editors and clippers
- TikTok/Reels/Shorts creators looking for gaming content
- Fans who want to make WW highlight reels
- Professional gaming content editors

### 3.3 The Clipping Flow

```
Clipper browses Wilder Stream Content Library
        ↓
Downloads raw footage from approved streams
        ↓
Edits into short-form clip (15s–3min, vertical 9:16)
        ↓
Posts on TikTok, Instagram Reels, YouTube Shorts (their own accounts)
        ↓
Submits clip URL to Wilder Clips for tracking
        ↓
Views tracked across all platforms
        ↓
$WILD payout based on total views
```

### 3.4 View-Based Payout Structure

Benchmarked against market rate ($3 CPM on Vyro, $0.50–2.00 CPM on TikTok Creator Fund):

| View Milestone | Rate | Cumulative Example |
|---|---|---|
| 0 – 1,000 views | 1 WILD per 100 views | 1K views = 10 WILD |
| 1,000 – 10,000 | 2 WILD per 100 views | 10K views = 190 WILD |
| 10,000 – 100,000 | 5 WILD per 100 views | 100K views = 4,690 WILD |
| 100,000 – 1,000,000 | 10 WILD per 100 views | 1M views = 94,690 WILD |

#### Clip Multipliers

| Multiplier | Bonus | Criteria |
|---|---|---|
| 🎯 Kill Clip | 1.5× | Clip features eliminations |
| 📺 2K+ Source | 1.3× | Clipped from 2K or higher footage |
| 🔥 Trending Audio | 1.2× | Uses trending sound/music |
| ⭐ Official Feature | 3× | WW reposts on official channels |
| 🏆 Weekly Winner | 2× | Top-performing clip of the week |

### 3.5 Quality Control

- **Auto-check:** Format, resolution, duration, WW branding present
- **AI Review:** Confirms real WW gameplay, not stolen/re-uploaded
- **Community Flagging:** Other clippers can report stolen content
- **Strike System:** 3 strikes (stolen content, fake views, spam) = permanent ban

### 3.6 Attribution Chain

Every clip tracks back to the original streamer:

```
Streamer uploads 2hr 4K session → earns 95 WILD (SQS payout)
        ↓
Clipper A makes a kill montage → 50K views → earns 1,890 WILD
Clipper B makes a cinematic edit → 200K views → earns 14,690 WILD
Clipper C makes a meme clip → 5K views → earns 90 WILD
        ↓
Original streamer earns 5% royalty on all clips from their footage
= additional 833 WILD from downstream clips
```

**The streamer royalty (5% of clipper earnings) is critical** — it incentivizes streamers to upload the highest quality footage possible, because better footage = more clippers use it = more royalties.

---

## 4. THE FULL FLYWHEEL

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│    ┌──────────┐     ┌──────────────┐     ┌──────────────┐  │
│    │  PLAYERS │────▶│ WILDER STREAM│────▶│CONTENT LIBRARY│  │
│    │ Stream WW│     │ Upload & Earn│     │ Raw Footage   │  │
│    └──────────┘     └──────────────┘     └───────┬───────┘  │
│         ▲                                        │          │
│         │                                        ▼          │
│   New players                            ┌──────────────┐   │
│   discover WW                            │ WILDER CLIPS │   │
│         │                                │ Clip & Earn  │   │
│         ▲                                └───────┬──────┘   │
│         │                                        │          │
│    ┌────┴─────┐                                  ▼          │
│    │ AUDIENCE │◀─────── TikTok / Reels / Shorts / X ◀──────│
│    │ Millions │         (organic distribution)              │
│    └──────────┘                                             │
│                                                             │
│    $WILD flows: WW Treasury → Streamers → Content Library   │
│                 WW Treasury → Clippers → Distribution       │
│                 Streamers earn royalties from clippers       │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### 4.1 Flywheel Economics

**Input:** $WILD tokens from treasury
**Output:** Organic reach, new players, content library, brand awareness

| Metric | Month 1 | Month 3 | Month 6 | Month 12 |
|---|---|---|---|---|
| Active Streamers | 25 | 100 | 500 | 2,000 |
| Hours Uploaded/Week | 100 | 800 | 4,000 | 16,000 |
| Active Clippers | 50 | 300 | 1,500 | 5,000 |
| Clips Published/Week | 200 | 2,000 | 15,000 | 50,000 |
| Weekly Views (all clips) | 500K | 5M | 50M | 200M |
| Weekly $WILD Distributed | 10,000 | 80,000 | 500,000 | 1,500,000 |
| Effective CPM (in USD) | ~$5 | ~$3 | ~$2 | ~$1.50 |
| New Players from Content | 200 | 3,000 | 30,000 | 150,000 |

*Effective CPM decreases as scale increases — content becomes the cheapest user acquisition channel at scale.*

### 4.2 Why This Beats Traditional Marketing

| | Traditional | Wilder Stream + Clips |
|---|---|---|
| **Content production** | Internal team films, edits | Players create it by playing |
| **Distribution** | Paid ads, organic posts | Hundreds of clippers post everywhere |
| **Cost model** | Fixed + CPM on ads | Variable, pay only for results |
| **Authenticity** | Brand-produced, feels corporate | Real players, real gameplay, real reactions |
| **Scale ceiling** | Limited by team bandwidth | Unlimited — more players = more content |
| **Player acquisition cost** | $5–15 per install (paid UA) | <$2 at scale via organic content |

---

## 5. ADDITIONAL REVENUE MECHANICS

### 5.1 Brand Campaigns (Revenue Stream)

Once the content library and clipper network reach scale, **external brands can post campaigns:**

- Energy drink brands, gaming peripheral companies, crypto projects
- They pay $WILD (or USD converted to $WILD) to run a clipping campaign
- Clippers create branded content featuring WW gameplay + sponsor
- **This turns WCN from a cost center into a revenue generator**

### 5.2 Premium Content Marketplace

Top-tier footage (4K, cinematic, professionally edited) can be:
- Licensed to media outlets, gaming publications
- Used in WW official trailers (streamer earns bonus)
- Sold as stock gameplay footage to other creators

### 5.3 The Labyrinth Integration

Clip earnings funnel through the Wilder economy:
- $WILD earned can be spent on Wilder Packs
- Wilder Pack purchases feed The Labyrinth (buy/burn mechanism)
- **Content creators become economic participants, not just marketers**

---

## 6. COMPETITIVE LANDSCAPE

| Platform | What They Do | What They Don't Do |
|---|---|---|
| **Vyro** | Clipping marketplace, $3 CPM, MrBeast-backed | No source content creation, no gaming focus, no token economy |
| **Medal.tv** | Auto-clip gaming highlights, 2M clips/day | No creator payouts, no distribution incentive |
| **Eklipse** | AI auto-clips from streams | Tool only, no marketplace, no payouts |
| **Pearpop** | Performance-based UGC challenges | Brand-focused, not gaming, no content library |
| **Allstar.gg** | Cloud-based gaming clip generation | CS2/LoL only, no payout model |
| **Wilder Stream + Clips** | **Full stack: source creation + content library + clipping marketplace + token-powered payouts + game-native** | **Nobody else has this** |

---

## 7. TECHNICAL ARCHITECTURE (HIGH LEVEL)

### Phase 1 — MVP (Weeks 1–4)

**Wilder Stream:**
- Web app: upload portal with drag & drop
- Auto-detection: resolution, duration, codec
- SQS calculator (resolution × duration × action density)
- $WILD balance tracking (database, not on-chain yet)
- Content library browser for clippers

**Wilder Clips:**
- Campaign/brief posting system
- Clip URL submission + view tracking (TikTok/IG/YT APIs)
- View-based $WILD payout calculator
- Creator profiles + leaderboard

**Shared:**
- Wallet connect (MetaMask / WalletConnect)
- Creator dashboard (earnings, analytics, history)
- Admin review panel (approve/reject/flag)

### Phase 2 — Scale (Weeks 5–12)

- Twitch/YouTube auto-import (connect account, auto-pull VODs)
- AI action density scoring (kill detection, combat analysis)
- Streamer royalty system (5% of downstream clip earnings)
- On-chain $WILD payouts (smart contract)
- Anti-fraud: view verification, duplicate detection, bot filtering
- Mobile app (upload from phone)

### Phase 3 — Ecosystem (Months 4–6)

- External brand campaign portal
- Premium content licensing marketplace
- Auto-clipping AI (suggest clip-worthy moments from uploads)
- Streamer OBS plugin (one-click upload after stream ends)
- Labyrinth integration ($WILD → Wilder Packs flow)

---

## 8. GO-TO-MARKET

### Launch Sequence

**Week 1–2: Closed Alpha**
- Invite 10–20 known WW streamers
- Seed the content library with 100+ hours of footage
- Onboard 20–30 clippers from the WW Discord community
- Test SQS formula and payout calibration

**Week 3–4: Open Beta**
- Open Wilder Stream to all players
- Launch first clipping campaign on WCN + cross-post to Vyro
- Announce $WILD reward pool: "100,000 $WILD up for grabs in launch month"
- Partner with 3–5 mid-tier gaming streamers (1K–10K concurrent) for paid launch streams

**Month 2: Public Launch**
- Full marketing push: "Get Paid to Play Wilder World"
- TikTok campaign showing real earnings (streamer makes X, clipper makes Y)
- Reddit/Discord/X community activation
- Weekly "Top Clipper" and "Top Streamer" spotlights on WW socials

**Month 3+: Scale**
- Referral program: streamers invite other streamers, earn 5% of their SQS payouts
- Seasonal campaigns: "Summer of Wiami" clip contest, holiday events
- External brand partnerships begin
- Target: 500 active streamers, 1,500 active clippers

---

## 9. RISKS & MITIGATIONS

| Risk | Impact | Mitigation |
|---|---|---|
| Low initial content quality | Poor clips reflect badly on WW brand | Minimum quality gates, SQS threshold for library inclusion |
| View botting / fraud | Wasted $WILD, unfair payouts | Anti-fraud layer: IP analysis, engagement patterns, platform API verification |
| $WILD price volatility | Creator earnings fluctuate | Peg payout rates to USD equivalent, adjust $WILD amounts quarterly |
| Platform API changes | TikTok/IG restrict view tracking | Multi-platform tracking, screenshot verification fallback |
| Content theft | Clippers steal from outside WW | AI fingerprinting of all library content, DMCA process |
| Low streamer adoption | Insufficient source content | Guaranteed minimum payouts for first 100 streamers, seed with internal footage |

---

## 10. SUCCESS METRICS

| KPI | 30-Day Target | 90-Day Target | 6-Month Target |
|---|---|---|---|
| Active Streamers | 50 | 200 | 1,000 |
| Weekly Hours Uploaded | 200 | 2,000 | 10,000 |
| Active Clippers | 100 | 500 | 3,000 |
| Weekly Clips Published | 500 | 5,000 | 25,000 |
| Total Weekly Views | 1M | 20M | 100M |
| New Players Attributed to Content | 500 | 5,000 | 50,000 |
| Content-Driven DAU Increase | +200 | +2,000 | +10,000 |
| Effective CPA (Cost Per Acquisition) | $8 | $4 | <$2 |
| $WILD Distributed Weekly | 25,000 | 150,000 | 500,000 |

---

## 11. BUDGET & TOKEN ALLOCATION

### Proposed Budget — Year 1 (USD-Pegged)

All payouts pegged to USD value, distributed in $WILD at monthly spot price.

| Category | Monthly USD | Annual USD | Monthly $WILD (@ $0.022) | Notes |
|---|---|---|---|---|
| Streamer Payouts (SQS) | $15,000 | $180,000 | ~682,000 | Scales with uploads |
| Clipper Payouts (Views) | $20,000 | $240,000 | ~909,000 | Scales with distribution |
| Streamer Royalties (5%) | $1,750 | $21,000 | ~79,500 | Auto-calculated |
| Launch Incentives | $10,000 | $10,000 | ~454,000 | One-time launch pool |
| Weekly Contests/Bonuses | $5,000 | $60,000 | ~227,000 | Top clipper/streamer rewards |
| **Total** | **~$51,750/mo** | **~$511,000/yr** | **~2,350,000/mo** | |

**At scale (Month 12 projections):**

| Category | Monthly USD | Monthly $WILD (@ $0.022) |
|---|---|---|
| Streamer Payouts | $80,000 | ~3,636,000 |
| Clipper Payouts | $120,000 | ~5,454,000 |
| Streamer Royalties | $10,000 | ~454,000 |
| Contests/Bonuses | $15,000 | ~682,000 |
| **Total at Scale** | **~$225,000/mo** | **~10,227,000/mo** |

*If $WILD appreciates (e.g., to $0.10), the same USD budget distributes ~78% fewer tokens. USD-pegging protects both sides: creators get predictable income, treasury manages token dilution.*

---

## 12. TEAM REQUIREMENTS

| Role | Responsibility | Timing |
|---|---|---|
| **Product Lead** | Own Wilder Stream + Clips product roadmap | Immediate |
| **Full-Stack Dev (×2)** | Build web apps, APIs, dashboard | Immediate |
| **AI/ML Engineer** | Action density scoring, gameplay verification, anti-fraud | Phase 2 |
| **Community Manager** | Onboard streamers, manage clipper community | Launch |
| **Content QA (×2)** | Review uploads, moderate clips | Launch |
| **Smart Contract Dev** | On-chain $WILD payout system | Phase 2 |

*Note: Jean Clawd (AI) handles: initial app build, content pipeline automation, analytics dashboard, trend monitoring, and clipper campaign management.*

---

## 13. DECISION REQUIRED

### For Team Sign-Off:

- [ ] **Approve the two-sided model** (Wilder Stream + Wilder Clips)
- [ ] **Approve SQS formula** and payout calibration
- [ ] **Approve $WILD token allocation** (~6.9M WILD Year 1)
- [ ] **Approve MVP scope** (4-week build, closed alpha first)
- [ ] **Approve launch timeline** (Alpha Week 1–2, Beta Week 3–4, Public Month 2)
- [ ] **Assign Product Lead** and dev resources
- [ ] **Confirm Vyro integration** for cross-platform clipping distribution

---

*"Every player becomes a content creator. Every content creator becomes a marketer. Every marketer earns $WILD. The game markets itself."*

**— Wilder World, 2026**
