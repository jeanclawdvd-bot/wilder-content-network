# WILDER CONTENT NETWORK — Comprehensive Brief

## Executive Summary

The Wilder Content Network (WCN) is a UGC-to-Earn platform that turns Wilder World's player base into a decentralized content army. Players stream and capture hi-res gameplay footage, upload their best clips to WCN, get verified, and earn $WILD tokens for accepted submissions. The WW team gets an infinite pipeline of authentic gameplay content for marketing — sourced directly from the community.

**One line:** *Play the game. Clip the kills. Get paid in $WILD.*

---

## The Problem

- WW needs daily content (Wilder Everydays, TikToks, Reels, dev logs)
- Internal team can't capture enough varied gameplay footage
- Players are ALREADY streaming and clipping — but WW gets none of it
- Current footage is low-res, poorly framed, unusable for marketing
- No incentive structure to produce quality content

## The Solution

A dedicated platform where players:
1. **Stream/record** Wilder World at minimum 2K resolution
2. **Upload** their best clips (kills, highlights, cinematic moments)
3. **Get verified** through automated quality checks + team review
4. **Earn $WILD** for every accepted submission

WW marketing team gets:
- Endless supply of verified, hi-res gameplay clips
- Community-sourced content with authentic energy
- Reduced production cost and time
- Built-in viral distribution (creators share their own clips)

---

## Platform Architecture

### 1. CONTENT TYPES & TIERS

| Tier | Type | Requirements | $WILD Reward |
|------|------|-------------|-------------|
| 🥉 Bronze | Raw Clip | 1080p min, 10-60s, gameplay only | 5 WILD |
| 🥈 Silver | Quality Clip | 2K+ res, kill/highlight moment, good framing | 15 WILD |
| 🥇 Gold | Edited Content | Montage, transitions, music sync, 15-60s | 50 WILD |
| 💎 Diamond | Viral Hit | Used in official WW channels, 10K+ views | 200 WILD |
| 👑 Creator | Ongoing | Consistent weekly submissions, quality track record | Monthly bonus pool |

### 2. UPLOAD REQUIREMENTS

**Technical Specs:**
- Minimum resolution: 1920x1080 (1080p)
- Preferred: 2560x1440 (2K) or higher
- Format: MP4, MOV, WebM
- Frame rate: 30fps minimum, 60fps preferred
- Max file size: 2GB
- Duration: 10 seconds — 5 minutes

**Content Guidelines:**
- Must be Wilder World gameplay (verified via AI frame detection)
- Kill moments, eliminations, highlights preferred (2x reward multiplier)
- No exploits, cheats, or hacked content
- No offensive player names/chat visible
- Clean audio (game audio preferred, commentary acceptable)

**Framing Guide (for maximum reward):**
- Record at 2K so crops to 1080p for 9:16 vertical
- Center the action on screen
- Capture the full kill sequence (approach → engagement → elimination)

### 3. VERIFICATION PIPELINE

```
UPLOAD → AUTO-CHECK → AI REVIEW → TEAM REVIEW → APPROVED → $WILD PAYOUT
  │          │            │            │              │
  │    Resolution?   WW gameplay?  Quality gate   Wallet credit
  │    Frame rate?   Kill moment?  Brand safe?    Notification
  │    Duration?     Framing?      Duplicate?     Leaderboard update
  │    File format?  Audio clean?
  │
  └── Rejected (with reason + tips to improve)
```

**Auto-Check (Instant):**
- Resolution ≥ 1080p
- Frame rate ≥ 30fps
- Duration 10s-5min
- Valid file format
- File not corrupted

**AI Review (< 5 min):**
- Frame analysis confirms Wilder World gameplay (HUD detection, asset recognition)
- Kill/elimination detection (HUD text, damage effects, kill feed)
- Framing quality score (action centered, proper composition)
- Audio quality check (no clipping, no silence)
- Duplicate/near-duplicate detection against existing library

**Team Review (< 24 hrs):**
- Final quality gate
- Brand safety check
- Content categorization and tagging
- Tier assignment (Bronze/Silver/Gold)
- Diamond tier flagged for official channel use

### 4. REWARD SYSTEM

**$WILD Token Integration:**
- Connect wallet (MetaMask, WalletConnect, Coinbase Wallet)
- Rewards accumulate in platform balance
- Withdraw to wallet anytime (min withdrawal: 10 WILD)
- Weekly bonus pool distributed to top 10 creators
- Streak bonuses: 7-day upload streak = 2x multiplier for a week

**Reward Multipliers:**
| Multiplier | Condition |
|-----------|-----------|
| 1.0x | Standard submission |
| 1.5x | Kill/elimination clip |
| 2.0x | 2K+ resolution |
| 2.0x | 7-day upload streak |
| 3.0x | Content used on official WW channels |
| 5.0x | Content goes viral (10K+ views on WW social) |

*Multipliers stack — a 2K kill clip on a streak used officially = 1.5 × 2.0 × 2.0 × 3.0 = 18x base reward*

### 5. CREATOR PROFILES & LEADERBOARD

**Profile Features:**
- Display name + avatar (pulled from WW account)
- Wallet address (connected)
- Total submissions / acceptance rate
- Total $WILD earned
- Content tier breakdown
- Streak counter
- Achievement badges

**Leaderboard Categories:**
- Most clips accepted (all-time / weekly / monthly)
- Highest quality score average
- Most $WILD earned
- Longest upload streak
- Most clips used on official channels
- Community favorite (voted)

**Achievements/Badges:**
- 🎯 First Blood — First accepted clip
- 🔥 On Fire — 7-day streak
- 💀 Kill Collector — 50 kill clips accepted
- 🎬 Director — 10 Gold-tier clips
- 👑 Wilder Creator — Diamond tier reached
- 🏆 Hall of Fame — Content featured on WW official channels 5+ times

### 6. CONTENT LIBRARY (Team-Facing)

The accepted clips feed into a searchable content library for the WW marketing team:

- **Search/filter** by: resolution, duration, content type (kill, cinematic, exploration), tier, creator, date
- **Download** original quality files
- **Auto-crop** to 9:16 with action-centered framing
- **Tag system** for content calendar planning
- **Usage tracking** — which clips have been used, where, when
- **Creator attribution** — automatic credit when clips are posted

### 7. WILDER STREAM PROGRAM

**For Live Streamers:**
- Register as a Wilder Streamer
- Stream at 2K+ resolution with WCN overlay
- AI monitors stream in real-time, auto-clips kill moments
- Auto-uploaded to creator's WCN queue for review
- Higher base reward for stream-sourced clips (consistent content)
- Featured streamer program for top performers

**Stream Requirements:**
- OBS/Streamlabs with WCN plugin (captures at source quality)
- Minimum 2K game resolution
- WCN overlay shows "Powered by Wilder Content Network" branding
- Stream to any platform (Twitch, YouTube, Kick) — clips pulled via API or local capture

---

## Technical Architecture

### Frontend
- **Framework:** Next.js 14 (App Router)
- **Styling:** Tailwind CSS + custom Wilder World design system
- **Wallet:** RainbowKit + wagmi for wallet connection
- **Upload:** tus.io resumable uploads (handles large files)
- **Video player:** Video.js with custom skin
- **State:** Zustand for client state

### Backend
- **API:** Next.js API routes → migrate to dedicated service as needed
- **Database:** PostgreSQL (Supabase) — creators, submissions, rewards
- **File storage:** Cloudflare R2 or AWS S3 (video files)
- **Queue:** BullMQ for processing pipeline (verification, AI review)
- **AI:** OpenAI Vision API for gameplay verification + content scoring
- **Blockchain:** ethers.js for $WILD token payouts (Ethereum L2)

### Infrastructure
- **Hosting:** Vercel (frontend) + Railway/Fly.io (backend workers)
- **CDN:** Cloudflare for video delivery
- **Monitoring:** Sentry + Posthog analytics
- **CI/CD:** GitHub Actions

---

## MVP Scope (2-Week Sprint)

### Week 1: Core Upload Flow
- [ ] Landing page with concept explainer
- [ ] Wallet connect (MetaMask)
- [ ] Video upload with auto-checks (resolution, format, duration)
- [ ] Upload queue / status tracking
- [ ] Basic creator profile

### Week 2: Review + Rewards
- [ ] Admin review dashboard
- [ ] Approve/reject with tier assignment
- [ ] $WILD balance tracking (database, not on-chain yet)
- [ ] Creator leaderboard
- [ ] Content library (team-facing)

### Post-MVP
- [ ] AI gameplay verification
- [ ] On-chain $WILD payouts
- [ ] Auto-crop tool for 9:16
- [ ] Stream program + auto-clipping
- [ ] Mobile app
- [ ] Community voting on submissions
- [ ] API for third-party integrations

---

## Revenue Model

WCN is a **cost center that generates revenue indirectly:**

1. **Content production cost savings** — $0 per clip vs. $50-500 for produced content
2. **Player retention** — incentive to keep playing and recording
3. **Organic marketing** — creators share their own clips (free distribution)
4. **Pack sales lift** — more content → more visibility → more players → more pack sales
5. **WILD token utility** — new use case drives demand for WILD

**Estimated economics:**
- 100 clips/day × 15 WILD avg reward = 1,500 WILD/day
- At current WILD price: ~$150/day content budget
- Equivalent to: 3-5 professional clips/day (normally $150-500 each)
- ROI: 10-50x on content production costs

---

## Competitive Analysis

| Platform | Model | WCN Advantage |
|----------|-------|--------------|
| Medal.tv | Free clips, no rewards | WCN pays creators in $WILD |
| Outplayed | Auto-clipping, no marketplace | WCN has review + reward pipeline |
| Twitch Clips | Platform-locked, no quality control | WCN enforces 2K+, curates quality |
| Axie Content | Token rewards but manual | WCN automates verification |

**WCN is unique:** First platform that combines UGC + quality verification + crypto rewards + direct pipeline into game marketing.

---

## Go-to-Market

### Launch Strategy
1. **Alpha (Week 1-2):** Internal team + 10 hand-picked streamers
2. **Beta (Week 3-4):** Open to top 100 active Wilders (by playtime)
3. **Public (Month 2):** Open registration, promoted on all WW channels
4. **Scale (Month 3+):** Stream program, partnerships, cross-game expansion

### Launch Content
- Announcement trailer (made from community clips — meta)
- "Earn WILD by Playing" campaign across X, TikTok, Instagram
- First 1,000 uploaders get bonus 100 WILD airdrop
- Weekly highlight reel made entirely from WCN submissions

---

## Success Metrics

| Metric | Month 1 | Month 3 | Month 6 |
|--------|---------|---------|---------|
| Registered creators | 100 | 500 | 2,000 |
| Daily uploads | 20 | 100 | 500 |
| Acceptance rate | 40% | 60% | 70% |
| Clips used in official content | 5/week | 20/week | 50/week |
| WILD distributed | 5K | 30K | 100K |
| Creator retention (weekly active) | 50% | 60% | 65% |

---

*Built for Wilder World by Jean Clawd — March 2026*
