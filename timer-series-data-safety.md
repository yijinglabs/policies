# Timer Series — Data safety

Plain-language explanation of what data is (and isn't) collected, plus a
reference for filling out the Play Console **Data safety** form. See also
`store/privacy-policy.md` for the full privacy policy.

## Summary

- **Hexagram Labs does not operate any server that collects, stores, or
  receives your personal data from this app.** There is no account/sign-in,
  and no analytics or crash-reporting SDK of ours.
- All app data — your series, period names, and any voice announcements you
  record — is stored only in the app's private storage on your device.
  Nothing is uploaded to us. Uninstalling the app deletes it all.
- The only data collected by anyone through this app is ad-related data
  collected by **Google AdMob**, and only in the free (ad-supported) build.

## Data collected by us: none

- No personal or app data is collected, stored, transmitted, or sold by
  Hexagram Labs.
- No analytics SDK, no crash-reporting SDK, no first-party backend.
- The `timer_series_free` build contains no ads SDK at all — nothing in this
  document's AdMob section applies to it.

## Data collected by Google AdMob (ad-supported build only)

The `timer_series` build shows a banner ad via Google AdMob. To serve and
measure ads, Google — not us — may collect:

- Advertising ID
- IP address / approximate location
- Device information (model, OS version, etc.)
- Ad interaction data (impressions, clicks)

This is governed by Google's policies, not ours:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data from apps that use its services:
  https://policies.google.com/technologies/partner-sites

### How to control or delete AdMob-related data

1. **On this device**: **Settings → Privacy → Ads** → "Delete advertising ID"
   (Android 12+) or "Opt out of Ads Personalization" (older versions). This
   stops personalized ads and resets/deletes the identifier Google uses.
2. **In your Google Account**: https://myaccount.google.com/data-and-privacy
   lets you view, manage, and delete ad-personalization data Google has
   collected across apps and services, including this one.
3. **In the app**: the one-time **Remove Ads** in-app purchase disables
   AdMob entirely going forward — the ads SDK stops being used and no further
   ad requests (or ad data) are sent to Google through this app. This doesn't
   retroactively delete data Google already collected; use step 1 or 2 for
   that.

## Play Console "Data safety" form reference

| Question | Answer |
|---|---|
| Does the app collect or share user data? | Yes — only via the AdMob SDK in the ad-supported build |
| Data types collected | Device or other IDs (advertising ID); approximate location (via IP, by Google) |
| Is data collection required or optional? | Optional — the ad-free build and the "Remove Ads" purchase avoid it entirely |
| Is data encrypted in transit? | Yes (handled by Google's SDK) |
| Can users request data deletion? | Yes — see "How to control or delete AdMob-related data" above |
| Purpose | Advertising or marketing (third-party ads) |
