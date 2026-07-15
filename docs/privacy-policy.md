# Privacy Policy

**Mindfulness Bell Premium**
**Last updated:** July 15, 2026

## Overview

Mindfulness Bell Premium ("the App") is developed by Khanh Mai. We are committed to protecting your privacy. This policy explains what data we collect, how we use it, and your rights.

## Data We Collect

### Data Stored on Your Device

- **Mindfulness observations** (journal entries you write)
- **Bell schedule settings** (times, intervals, sound preferences)
- **Bell acknowledgment history** (for streak and statistics tracking)
- **App preferences** (language, appearance, notification settings)

This data is stored locally on your device using an encrypted database. It is never shared with third parties.

### Data Collected for App Functionality

- **User ID** — If you sign in with Apple, we store an anonymous user identifier to enable optional cloud sync between your devices. We do not access your name or email address (Apple's "Hide My Email" is respected).
- **Purchase history** — We verify your subscription status through Apple's StoreKit and RevenueCat to unlock premium features. Purchase data stays with Apple and RevenueCat; we only receive entitlement status.

### Optional Cloud Sync (Premium Feature)

If you enable cloud sync, your observations, settings, and acknowledgments are encrypted and stored on Supabase (our cloud provider). Data is encrypted before leaving your device. You can delete all cloud data at any time from Settings > Account > Delete Account.

### Analytics

We use **TelemetryDeck** for pseudonymous, aggregated usage analytics. "Pseudonymous" means signals carry a one-way hashed identifier so we can count distinct users — we cannot reverse it to identify you. TelemetryDeck is a privacy-first analytics service that:

- Does **not** use cookies or device fingerprinting
- Does **not** collect personally identifiable information (PII)
- Does **not** track users across apps or websites
- Does **not** share data with advertisers or data brokers
- Collects only usage patterns (e.g., which screens are viewed, feature usage counts)

**What is collected:** in-app events such as screen views, feature usage counts, bell schedule shape (interval and window — never journal content), purchase funnel outcomes (success/cancel/failure category — never payment details), plus **automatic session signals** sent by the TelemetryDeck SDK itself (app launch, session start, app version, OS version, device model class, language).

**Analytics is on by default** and disclosed here. You can turn it off at any time in **Settings › Privacy › Usage Analytics**. Turning it off takes effect immediately: custom events stop instantly and the analytics SDK is shut down, so its automatic session signals stop too. While analytics is off, the SDK is never started on later launches.

**Retention:** analytics signals are retained by TelemetryDeck in aggregated form; raw signals age out per [TelemetryDeck's privacy policy](https://telemetrydeck.com/privacy/). We store your consent choice (on/off, version, timestamp) only on your device.

We do **not** use Apple's App Tracking Transparency (ATT) because we do not track users across apps or websites.

## Data We Do NOT Collect

- Email address
- Device identifiers (IDFA, IDFV)
- Location data
- Contacts, photos, or other personal data
- Advertising or tracking data

## Third-Party Services

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Apple StoreKit | Subscription purchases | [Apple Privacy](https://www.apple.com/privacy/) |
| RevenueCat | Subscription management | [RevenueCat Privacy](https://www.revenuecat.com/privacy/) |
| Supabase | Cloud sync (optional) | [Supabase Privacy](https://supabase.com/privacy) |
| TelemetryDeck | Pseudonymous usage analytics | [TelemetryDeck Privacy](https://telemetrydeck.com/privacy/) |

None of these services receive data for advertising purposes.

## Your Rights

- **Delete your data:** Go to Settings > Account > Delete Account to remove all cloud data and your account.
- **Export your data:** Premium users can export all observations from Settings.
- **Opt out of sync:** Cloud sync is optional and only available to premium subscribers who sign in.
- **Opt out of analytics:** Turn off Settings › Privacy › Usage Analytics. All analytics — including the SDK's automatic session signals — stop immediately.

## Children's Privacy

The App does not knowingly collect data from children under 13.

## Changes to This Policy

We may update this policy from time to time. Changes will be posted on this page with an updated date.

## Contact

If you have questions about this privacy policy, contact us at: blueblazedev@outlook.com
