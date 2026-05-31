# SleepTyme

iOS app that calculates optimal wake-up times based on 90-minute sleep cycles, with a smart alarm that fades in gently instead of jarring you awake.

**By SNE Interactive LLC** · [On TestFlight](https://testflight.apple.com/join/MHNJsZe3) · App Store coming soon

---

## What it does

- **Night Sleep calculator** — enter a bedtime, get 4 ranked wake-up times (Optimal, Great, Good, Minimum) that align with the end of a sleep cycle so you avoid mid-cycle grogginess.
- **Age-specific science** — separate parameters for Adult (90-min cycles, 14-min onset), Teen (90-min cycles, 20-min onset, circadian delay), and Infant (50-min cycles, REM-dominant).
- **Optimal Nap mode** — 5 nap durations from the 20-min Power Nap to the 120-min Recovery Nap, including a Danger Zone warning for the 45-min trap that wakes you mid-deep-sleep.
- **Smart wake-up alarm** — taps to arm; rings at the selected time even when your phone is locked or on silent; the chime starts at a low volume and gradually fades to full over 30 seconds for a gentle wake.
- **Quick Alarm** — set an alarm for any arbitrary time, independent of the cycle calculator.
- **Apple Health integration (opt-in)** — read your recent sleep average; write your planned sleep schedule.

## Pricing

- **Free** — Night Sleep calculator (Adult mode), nap previews
- **SleepTyme Pro** — $1.99 one-time purchase unlocks:
  - The smart alarm with gradual fade-in
  - Infant and Teen age modes
  - Full Optimal Nap mode with alarm
  - HealthKit integration

No subscription. No ads. Buy once, own forever. Family Sharing supported.

## Privacy

SleepTyme does not collect, transmit, or share any personal information. All data stays on your device. No accounts, no analytics, no third-party SDKs, no servers.

📄 [Full Privacy Policy](PRIVACY.md)

## Support

Email: info@sneinteractive.com

For billing or refunds, please contact Apple Support directly through your Apple ID.

## Tech

- iOS 17+
- Swift 5.9 + SwiftUI + StoreKit 2 + HealthKit + AVFoundation + UserNotifications
- @MainActor / ObservableObject state
- No third-party dependencies

## About SNE Interactive

SNE Interactive LLC builds focused, privacy-respecting iOS apps.

---

*Bundle ID: `com.sneinteractive.whentosleep` · Team: SNE INTERACTIVE LLC*
