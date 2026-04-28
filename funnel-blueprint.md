# Funnel Blueprint - End-to-End for Kit

> Full proposed funnel architecture. Drop into a 90-day install. Each piece is buildable independently if budget is staged.

---

## Current Funnel (Mapped)

```
[IG / TikTok / YouTube content] → [Bio link → slickwithkit.com homepage]
                                          ↓
                                  [Either /cym-vsl course funnel ----- works]
                                  [Or /cta application form ---------- LEAKS HERE]
                                                              ↓
                                                     [Manual setter follow-up - slow]
                                                              ↓
                                                     [Some prospects book a call]
                                                              ↓
                                                  [44% cancel before showing up]
                                                              ↓
                                                       [Held call - close ~1 in 3]
```

Two paths. One works (course funnel). One leaks badly (1:1 funnel).

---

## Proposed Funnel (90-Day Install Target)

```
                              [Track A reels]    [Track B reels]
                                       \              /
                                        \            /
                                         [Bio link router]
                                         /     |       \
                                        /      |        \
                          [/free-quiz][/podcast][/start]
                              ↓           ↓        ↓
                  [Quiz email capture][Spotify][Homepage]
                              ↓                       \
                      [10-day welcome flow]            \
                              ↓                         \
                   [Tier 1: Membership $39/mo OR Course $597] OR  [/1-1-vsl page]
                                                                        ↓
                                                                  [VSL - 3-5 min]
                                                                        ↓
                                                            [Application form embed]
                                                                        ↓
                                                              [Auto Calendly redirect]
                                                                        ↓
                                                              [Pre-call sequence: 3 touches]
                                                                        ↓
                                                                  [Held call - Kit closes]
                                                                        ↓
                                                                  [1:1 onboarding flow]
```

### What's new vs. current

| Layer | Current | Proposed |
|---|---|---|
| Top of funnel | Single content track | Track A + Track B (see `content-strategy.md`) |
| Bio link | → homepage | → 3-route router (quiz / podcast / start) |
| Lead capture | Weekly tips signup only | Quiz funnel ("What's your dating archetype?" or similar) |
| Email nurture | Probably thin / nothing | 10-day welcome flow |
| Course funnel | `/cym-vsl` works fine | UNCHANGED |
| Membership | Unverified | Verify; if exists, integrate. If not, build. |
| **1:1 funnel** | **Form → manual setter** | **VSL → form → auto-Calendly → pre-call sequence** |
| Pre-call nurture | None | 3-touch sequence (video, case study, SMS) |
| Setter motion | Pitching | Confirm + protect calendar (see `dm-setting-playbook.md`) |
| Retargeting | Not visible / broken | Meta Pixel + GA4 installed cleanly |
| Paid traffic | None | Phase 2: Meta retargeting + cold to top reels |

---

## Build Phases

### Phase 1 - The Critical Plumbing (Weeks 1-3)

**Goal:** Stop the bleeding on the $4K funnel.

1. Build `/1-1-vsl` page (premium dark, Closers Circle Pro aesthetic, embedded VSL above the fold, application form below)
2. Film and edit 3-5 min VSL (see `vsl-preview.md`)
3. Replace `/cta` form with new application form that auto-redirects to Calendly
4. Set up Calendly with proper buffers, screening question, phone capture for SMS
5. Build pre-call nurture: confirmation video, case study email, SMS reminder
6. Train setter / Kit on the new playbook (`dm-setting-playbook.md`)
7. Install Meta Pixel + GA4 cleanly

**Outcome:** $4K funnel converts. Cancel rate drops. Held calls per month +50%.

### Phase 2 - Top-of-Funnel Capture (Weeks 4-7)

**Goal:** Stop losing 80K-150K reach to a weak email capture.

1. Build quiz funnel (e.g. "What's your dating archetype?") - 5-7 questions, results page, email gate
2. Build 10-day welcome flow (email sequence introducing Kit, Track A and Track B clips, course soft-pitch on day 7)
3. Update bio link to a 3-route router: quiz / podcast / start
4. Update IG content cadence to drive specific hooks to specific routes (Track A → quiz, Track B → 1:1)

**Outcome:** Email list grows by 1-2K/month from existing reach. Course buyers from email +20-30%.

### Phase 3 - Brand and Content Compound (Weeks 4-12, parallel)

**Goal:** Shift the audience demo over a quarter so the $4K funnel stays full of qualified buyers.

1. Photoshoot + B-roll day (see `content-strategy.md`)
2. 30 Track B hooks scripted, 12 produced
3. 6-10 podcast guest outreaches, 4-6 episodes recorded
4. Bio + brand framing updated
5. Track B reels and carousels start posting

**Outcome:** Application form-fillers shift from 22-32 frustrated demo to 30-45 wealth demo. Close rate on $4K rises because the pre-sold buyer is qualified.

### Phase 4 - Paid Traffic + Retargeting (Weeks 9-12+)

**Goal:** Buy predictable lead flow on top of organic.

1. Identify top 3 Track A reels by engagement (the volume engine)
2. Identify top 3 Track B reels by conversion intent (the wealth engine)
3. Run paid as boosted posts to lookalike + interest audiences
4. Retargeting: anyone who watched 50%+ of a Track B reel sees the VSL within 24 hours
5. Budget: £2-5K/mo to start. Scale based on CPL and close-rate data.

**Outcome:** Predictable paid lead flow. Doubles top of funnel without doubling content output.

---

## Tech Stack (Proposed)

| Layer | Tool |
|---|---|
| Site (course funnel) | Squarespace (KEEP - works) |
| Site (1:1 funnel) | Static HTML on Vercel/Netlify, OR Squarespace if integrated cleanly |
| Application form | Tally or Typeform with redirect |
| Calendar | Calendly or Cal.com |
| Email + SMS | ConvertKit (or Klaviyo) + Twilio for SMS |
| Pixel | Meta Pixel + GA4 |
| Quiz | Interact or Tally |
| Membership (if missing) | Skool OR Whop OR keep Squarespace Member Areas (decide based on Kit's preference and existing customer base) |
| Paid ads | Meta Ads Manager (Phase 4) |
| Analytics + dashboards | Plausible or Fathom for site-side, Stripe dashboard for revenue |

Estimated tooling cost: ~£200-400/month all-in once stable.

---

## Pricing Reposition (Phase 2 Conversation)

After the VSL is in place and the funnel is converting at a clean rate, raise the 1:1 price.

**Current:** $4,000
**Proposed Phase 2 price:** $6,500-7,500 with payment plan ($2,500 down + 2× $2,500)
**Justification:** Kit is underpriced vs. market (Hussey $10K/hr, Stephan $497/session, London agency tier £2-10K). With theatre presence + viral TikTok hits + BBC-adjacent credibility, $4K leaves $2-3K per close on the table.

Don't lead with this on the call. It's a Phase 2 conversation once the mechanics are working.

---

## Revenue Model Projection (90-Day Stack)

Conservative numbers, current audience size unchanged:

| Metric | Today | Day 90 |
|---|---|---|
| Held calls/month | 5 | 8-10 |
| Close rate on held | ~30% | ~30-40% (better-qualified pre-sold demo) |
| 1:1 closes/month | ~1.5 | ~3-4 |
| 1:1 price | $4K | $4K (or $6.5K Phase 2) |
| 1:1 revenue/mo | $6K | $12-16K (or $20-26K Phase 2) |
| Course buyers/mo | ~10-20 | ~15-25 (from quiz funnel) |
| Course revenue/mo | ~$6-12K | ~$9-15K |
| Membership | unverified | $1-8K depending on existence |
| **Total monthly** | **~$15-25K** | **~$25-40K (Phase 2: $35-55K)** |

That's a realistic 50-100% revenue lift in 90 days from same audience size.

---

## Hand-Off / DFY Pitch Framing

For the call, don't pitch the entire 4-phase plan. Pitch Phase 1 only.

> "What I'd suggest is we start with the $4K funnel. Three weeks. We build the VSL page, fix the form, install the pre-call sequence. By week 4 you should see the cancellation rate drop and the held-call count go up. We measure for a month, then we either expand to the content shift and the quiz funnel, or we don't - your call.
>
> The whole point is you don't have to manage any of it. You film one VSL day. You record the case study video. After that, we build, we test, we report. You keep doing what you're doing - content, podcast, acting. We install."

That's the offer. Don't oversell.
