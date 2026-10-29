# Privacy Policy

Last updated: October 29, 2026

## Who we are

MenuSwap helps you pick restaurant meals that fit your calorie and protein goals. This policy explains what data we handle and what we do not do.

## What we store on your device

Most of your personal data stays on your phone in local storage (AsyncStorage), including: name or display name; goal, sex, age, height, weight, target weight, activity level; allergies and food preferences; daily calorie and protein targets; food log entries (meal name, macros, meal type, date); country and timezone (for “today” in your local day); theme preference (light/dark); and reminder preferences (which local alerts you opted into). Food logs are pruned after about 30 days on device.

## Local reminders

If you turn Reminders on in Profile, MenuSwap schedules local notifications on this device only (meal logging, a Find nudge before ordering, an evening check-in for calories/protein room, and a weekly Insights reminder). These are not remote push from our servers — nothing is sent to us to deliver them. You can turn groups or the master switch off anytime; Delete Account also clears scheduled alerts.

## Account & cloud

When you create a cloud account, we store the minimum needed for your account (for example email and profile fields, nutrition targets, and food log entries) with our database provider (Supabase), so the same account can sync across devices. Delete Account removes your app data from our database and, when enabled, deletes your authentication account. Demo/local mode keeps data on the device only and does not sync to the cloud.

## Nutrition data

Menu calories and macros come from a curated restaurant nutrition database bundled with the app (MenuStat-derived / verified menu facts). We do not invent nutrition numbers with AI. If a food cannot be matched, we say so rather than guessing macros.

## Artificial intelligence (honest use)

AI is used only to interpret what you typed (for example turning “something sweet” into a search for desserts) and sometimes to phrase short explanations for swaps. AI does not invent calorie or protein values. When AI runs, the text of your craving or selected item names may be sent to third-party model providers so they can return a structured search preference. Today that can include Google Gemini and/or Groq, depending on configuration. Do not put secrets or unrelated personal data into craving search.

## Third parties that may receive data

Depending on features enabled in your build: Google Gemini and/or Groq (craving parsing / short copy); optionally Spoonacular or USDA APIs if those keys are configured (menu or food lookups); Supabase (auth and cloud profile when enabled); Google favicon service for restaurant letter/logo images (restaurant name only). We do not sell your personal data. We do not use your food log to train public AI models.

## API keys in the app

Some builds embed public client keys (for example EXPO_PUBLIC_* keys) so the phone can call those APIs directly. That is convenient for development but is not ideal for production. Production should route sensitive calls through our own backend so keys are not shipped in the app binary. Until then, treat client keys as limited and rotatable.

## Analytics & advertising

We do not currently run third-party advertising SDKs or sell ads in the app. We do not currently send your food log to analytics products. If we add analytics later, we will update this policy and App Store privacy labels before shipping.

## Children

MenuSwap is not directed at children under 13 (or the minimum age in your region). Do not use the app if you are under that age.

## Your choices

You can edit profile details in Profile. You can manage Reminders (or turn them off) in Profile. You can clear food history by deleting meals or using Delete Account. Delete Account permanently removes MenuSwap data for your account (profile, targets, logs, theme, reminder settings, and related caches), cancels scheduled local alerts, and deletes synced cloud data when you use a cloud account. This cannot be undone.

## Health disclaimer

MenuSwap is not medical advice. Calorie and protein targets are estimates from formulas and the goals you enter. Talk to a clinician for diet or medical decisions. Restaurant nutrition can change; always trust the restaurant’s current labeling when it matters.

## Contact

Questions or data requests: support@menuswap.app. If you need a copy of your data before deleting the account, contact us first while the data still exists.
