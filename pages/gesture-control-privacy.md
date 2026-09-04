---
layout: page
title: "Gesture Control Privacy Policy"
subheadline: "Privacy Policy"
teaser: "How Gesture Control handles motion, settings, diagnostics, and purchase information."
permalink: "/gesture-control/privacy/"
---

**Effective date: September 4, 2026**

Gesture Control is an Android utility that lets you trigger actions such as toggling the flashlight, opening the camera, launching a selected app, or vibrating the device through motion gestures. This Privacy Policy explains what information the app handles.

## Information processed on your device

Gesture Control processes linear-acceleration, gyroscope, and, when available, proximity-sensor readings to recognize Double Chop, Twist, and Shake gestures. Sensor processing occurs locally on your device. The app does not upload raw motion samples to us.

The app stores settings locally, including sensitivity, Pocket Protection, the selected Shake action, the package name of a selected app, onboarding state, and locally derived calibration thresholds.

## Diagnostic traces and activity

When a Double Chop is detected, the app may save the preceding motion-sensor window as a diagnostic CSV file in private app storage. These traces help investigate missed or accidental detections. Retention is limited to approximately 50 files or 10 MiB. Diagnostic traces are not uploaded automatically.

Recent gesture activity displayed in the app remains on the device. You can delete individual entries, selected entries, a day of entries, or all displayed activity. Removing the app clears its private data according to Android behavior.

## Permissions

- **Camera** is required by Android to control the device flashlight. Gesture Control does not use this permission to capture photos or video.
- **Notifications** allow the foreground monitoring service to remain visible and provide a Stop action.
- **Foreground service and wake lock** allow user-enabled gesture monitoring to continue while the app is in the background or the screen is off.
- **Vibration** is used only when you assign vibration to a gesture.
- **Network access** is used for Google Play Billing and to open Gesture Control legal pages inside the app.

## Purchases

Gesture Control may offer an optional one-time Lifetime Pro purchase through Google Play. Google Play processes payment information and returns product and purchase status to the app. The app validates the expected product and purchase token shape locally and acknowledges completed purchases through Google Play. We do not receive or store your full payment-card details.

## Accounts, advertising, and analytics

Gesture Control does not require an account, does not contain advertising, and does not use third-party behavioral analytics. We do not sell personal information.

## Legal pages and website access

When you open Privacy or Terms from the app, an embedded browser loads pages from `tcool.ltd`. Standard web-server or hosting logs may process technical request information such as IP address, browser user agent, and request time for security and delivery purposes.

## Sharing and retention

We do not operate a server-side database for Gesture Control motion data, activity, settings, calibration profiles, or diagnostic traces. Data remains in Android private app storage until removed by the app, cleared through Android settings, or deleted when the app is uninstalled.

If you contact us by email, we receive the information you choose to provide and use it only to respond and maintain reasonable support records.

## Children's privacy

Gesture Control is not directed to children under 13. We do not knowingly collect personal information from children.

## Changes to this policy

We may update this policy when the app or its data practices change. The latest version will be published on this page with a revised effective date.

## Contact

Questions about this policy can be sent to [dev@tcool.ltd](mailto:dev@tcool.ltd).

