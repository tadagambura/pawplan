# PawPlan: Spec

**Your pet's care, all in one place** · #20 of 31 · Wave 2: Recurring keepers · Used: Daily · Harder · Revenue potential: Medium · Family, Pets & Plants · Source: New (Claude)

## One-liner

Feeding, walks, flea and worming treatments, vaccinations, vet appointments, medication and weight, with reminders and a shared log so the whole household knows whether the dog's been fed.

## Problem / audience

- **Who it's for:** Dog and cat owners, multi-pet households.
- **The problem it solves:** 'Has the dog been fed?', forgotten flea treatments and missed vaccinations.
- **Example:** Two flatmates see the dog's breakfast has been logged, and both get the monthly flea-treatment reminder.

## MVP features (ship with only these)

1. Pet profiles
2. Recurring treatment and vaccination reminders
3. Feeding and walk log
4. Vet appointments and medication
5. Weight tracking

## Not in MVP

- Shared household log (sync)
- Vet record export
- Multiple pets

## Monetisation

| Model | Detail |
|---|---|
| Free | One pet, with ads |
| Premium | £2.49/month: multiple pets, sharing, records export |
| Affiliate | Insurance and food, clearly labelled |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Treatment and feeding reminders |
| Tiny win | Log a feed, walk or treatment |
| Progress | Care-on-track status; walk streaks |
| Share | Pet milestone cards |
| Next step | The next treatment is scheduled automatically |
| Cadence | Daily/monthly |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Fed: the pet does a happy wiggle
- Walk logged: the pet drags the stickman along on the lead
- Treatment done: the pet puts on a tiny superhero cape
- Pet's birthday: party hat, tail-chasing
- Weight logged: the pet stands proudly on the scale and flexes

**Line we don't cross:** These are real animals: never animate illness, injury or death.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app; sharing needs Supabase.
- **Data:** On the device; sync for sharing.
- **Backend:** Device only; shared data once household sharing is added. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Pet care tips; Puppy and kitten first year; Pet costs
- **Shareable output:** Pet milestone cards

## Risks

No veterinary advice: always signpost to a vet. Sharing needs a backend.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
