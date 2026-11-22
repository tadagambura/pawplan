# PawPlan: Spec

**Your pet's care, all in one place** · #27 of 33 in the build order · Harder · Revenue potential: Medium · Family, Pets & Plants · Source: New (Claude)

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

Prices are starting points; test before committing.

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

## Platform & data

- **Platform:** Expo app; sharing needs Supabase.
- **Data:** On the device; sync for sharing.
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
- [ ] Added to growth-engine as an app config
