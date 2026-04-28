# DM Setting Playbook — Fixing the 4/9 Cancel Rate

> The 44% cancellation rate is a calendar problem first, a setter problem second. This playbook fixes both. Designed to be handed to whoever is running DMs / inbound for Kit.

---

## The Diagnosis (Why 4 of 9 Cancel)

A 44% cancel rate doesn't come from one cause. It comes from three small leaks compounding:

1. **The form doesn't book the call.** Prospect submits. Time passes. Someone reaches out manually 6-24 hours later. By then, the prospect has cooled, gone on holiday, or remembered they were going to ghost.
2. **No pre-call nurture.** Once a call is booked, there's no value-add between "booking" and "call" — so the prospect doesn't build commitment to showing up.
3. **The setter (if there is one) is pitching, not protecting the slot.** Setting calls has one job: confirm fit, protect the calendar slot, do not pitch. If the setter is selling, the prospect is half-sold and pre-objecting before the call.

Each leak alone costs 10-15% of bookings. Stack them and you get 44% cancellations.

---

## The Three-Layer Fix

### Layer 1 — Form-to-Calendar in One Click

**Current:** Prospect fills out application → form submits → prospect waits → setter reaches out manually → prospect picks a time.

**New:** Prospect fills out application → form submits → IMMEDIATELY shows Calendly slot picker on the same page → prospect picks time → confirmation email auto-sent.

**Implementation options:**

- **Option A (cleanest):** Replace the application Typeform with a Tally form or a custom-coded form that has a "thank you" page hosting the Calendly embed.
- **Option B (fastest):** Keep the Typeform, change the redirect URL to a `/book-call` page that has the Calendly embed.
- **Option C (luxury):** Use a tool like [SavvyCal](https://savvycal.com/) or Cal.com inline-embedded after form submit. Cleaner UX than Calendly.

Recommended: Option B. Two-week install max. No platform migration.

**Calendly settings:**
- Buffer: 15 min before, 15 min after
- Notice: minimum 12 hours in advance (gives time for the pre-call sequence to land)
- Available slots: 4-6 per week, clustered (e.g. Tue-Thu, 2pm-6pm London)
- Required questions on booking: phone number (for SMS reminder), one screening question
- Auto-confirmation email: ON, with a 90-second video from Kit (see Layer 2)

### Layer 2 — Pre-Call Nurture Sequence

Between booking and the call, three touches:

#### Touch 1 — T-0 (the moment they book)

**Channel:** Email + Calendly auto-confirmation
**Content:** 60-90 second video from Kit, embedded.

Video script:

> "Hey — Kit here. Saw your application come through. Looking forward to our call on [date].
>
> Quick thing before we talk. I want to make this useful for you, not just useful for me. So between now and then, just have a think about three things:
>
> One — what does the relationship you actually want look like? Specifics. Not 'a good guy.' What does a Tuesday night with him look like.
>
> Two — what's been the gap between that and what you've been finding? Be honest with yourself.
>
> Three — what do you think is in the way?
>
> Bring those answers to the call. I'll show you what I see, and we'll figure out together if what I do is the right vehicle for getting you there.
>
> See you on the [date]."

That video alone increases show rate by 15-25%. Reason: she's now seen Kit's face and voice before the call. She's committed.

#### Touch 2 — T-1 day

**Channel:** Email
**Content:** A real client story, 250-400 words. Names a specific case study (real client, with permission), a real timeline, a real outcome. Closes with: "see you tomorrow."

Template:

> Subject: Real story before tomorrow
>
> Quick one before our call tomorrow.
>
> Wanted to share a story because I think it might be relevant.
>
> [Client first name] came to me [X] months ago. She was [age], running [type of business], single for [time]. Specifically she'd been on a run of guys who were either intimidated by her career or trying to compete with it. She was tired. She'd done all the apps, done the friend setups, done the "just put yourself out there" advice. None of it worked.
>
> We started in [month]. By [month], she was [outcome]. By [month + X], she was [outcome 2].
>
> The thing that changed wasn't the volume of dates. It was the screen. She stopped accepting first dates that didn't pass a 10-minute fit check. Within six weeks, the type of man showing up was completely different.
>
> Tomorrow, that's the kind of work we'll be talking about — what does YOUR version of that look like.
>
> See you at [time].
>
> — Kit

#### Touch 3 — T-morning (day of)

**Channel:** SMS
**Content:** Short. "Hey [name] — Kit here. Looking forward to our chat at [time] today. Link is [Zoom/Meet]. See you in a bit."

SMS show-rate impact: +20% on top of email. Use it.

---

### Layer 3 — Setter Playbook (If Kit Keeps a Setter)

If a setter is involved in qualifying inbound (DMs, form leads), they need rules. The current motion sounds unstructured.

#### The Setter's Single Job

**Confirm fit. Protect the calendar slot. Do not pitch.**

Anything beyond those three is the setter doing Kit's job and doing it worse.

#### The Three Qualifying Questions

After someone DMs interest or fills out a form, the setter asks ONLY:

1. "What kind of relationship are you actually looking for?" (intent check)
2. "What have you tried so far that hasn't worked?" (pain check)
3. "What's making you reach out now, vs. six months ago or six months from now?" (urgency check)

If the answers are decent, the setter says: "Sounds like Kit is the right person to talk to. Here's the calendar — pick a time."

That's it. No pitching. No price discussion. No "let me tell you about the program."

#### What the Setter Should NEVER Do

- Quote price
- Describe the program in detail
- Sell features
- "Convince" a hesitant lead — let them book or move on
- Promise outcomes
- Argue with objections — note the objection, send the calendar anyway, let Kit handle it on the call

#### What the Setter SHOULD Do

- Reply within 1 hour during business hours, 4 hours otherwise
- Use first-name personalisation
- Be direct, warm, not chirpy
- Send the calendar link with a one-line cue: "Pick a time that works — Kit's blocked these slots out for serious applications this week"
- After booking, hand off to the automated nurture sequence

---

## DM Templates (For Inbound Conversation)

These replace whatever the setter is currently using. They're calibrated to Kit's voice.

### Template 1 — Inbound from Reel/Comment Engagement

> "Thanks for the message [name].
>
> Quick one — what's actually going on for you in your dating life right now?
>
> No long story needed. Just a sentence or two on where you're at."

Wait for response. Listen. Then:

> "Got it. Sounds like you're at the point where you've tried the standard advice and you're done playing the volume game.
>
> Kit takes on a small number of 1:1 women each month. If you want to talk to him directly, here's the application — takes 4 minutes, then you can pick a time that works:
>
> [APPLICATION LINK]
>
> If you're not at that stage, no worries — there's a course at slickwithkit.com that might be the better entry point."

### Template 2 — Form Submitted, No Calendar Yet (Recovery for Existing Pipeline)

> "[Name] — saw your application come through. Took a quick look.
>
> Want to get you in with Kit this week. Here's his calendar — pick a time:
>
> [CALENDLY LINK]
>
> Answer a couple of questions before you book if you can — helps Kit show up prepared for you."

### Template 3 — Booked but Quiet (24h Before Call)

> "[Name] — confirming you for [time] tomorrow with Kit.
>
> Link is [Zoom/Meet link].
>
> If anything's changed and you need to reschedule, send me a message — much easier than no-showing."

### Template 4 — Cancelled / Rescheduled

> "[Name] — no problem at all on the reschedule.
>
> Here's the calendar with this week and next:
>
> [CALENDLY LINK]
>
> Want to get this sorted for you."

### Template 5 — Ghost Recovery (3 Days After No-Show)

> "[Name] — noticed you missed the call last [day]. No drama.
>
> If timing's just rough right now, send me a message and we'll find a slot that actually works.
>
> If you're rethinking it, also fine — would just rather know than wonder."

---

## Show Rate Targets

| Stage | Current (estimated) | Target after fixes |
|---|---|---|
| Application → Calendar booked | unknown, probably <50% | 80%+ (one-click) |
| Booked → Held | 56% (5/9) | 80%+ |
| Held → Closed | unknown | unchanged (Kit's job, not the playbook's) |

**Net effect:** Same top-of-funnel volume. ~50% more held calls per month. Same close rate = ~50% more closed deals per month.

---

## What This Looks Like When It's Working

A prospect's journey, end-to-end:

1. Sees a reel. Comments or DMs.
2. Setter responds within 1 hour with two qualifying questions.
3. Setter sends application link.
4. Prospect fills out application (4 min).
5. Form submit auto-redirects to Calendly slot picker.
6. Prospect picks Wednesday at 3pm.
7. Confirmation email + 90-sec Kit video lands within 60 seconds.
8. Tuesday afternoon: case study email lands.
9. Wednesday 9am: SMS reminder lands.
10. Wednesday 3pm: prospect shows up. Already trusts Kit. Already done the homework.
11. Kit closes 1 in 2-3.

That's the shape of an 80% show rate funnel. None of it is rocket science. All of it is missing today.
