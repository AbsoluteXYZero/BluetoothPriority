# Privacy Policy — Bluetooth Priority

*Last updated: October 28, 2026*

Bluetooth Priority ("the app") is a Bluetooth audio management utility for Android. This policy describes how the app handles information.

## No data is collected or transmitted

The app does not collect, store, transmit, or share any personal information, usage data, analytics, or device identifiers with the developer or any third party. All data the app generates (event logs, settings, device preferences) is stored exclusively on your device and never leaves it, unless you choose to send a support request (see below).

## Bluetooth permissions

The app requests Bluetooth permissions (`BLUETOOTH_CONNECT`, `BLUETOOTH_SCAN`) solely to detect connected audio devices and enforce your configured audio routing policy. Device names and MAC addresses are used only in memory at runtime and in the on-device event log. They are never transmitted off-device.

## Shizuku

The app requires Shizuku, a third-party privilege manager, to access additional Bluetooth APIs. No data is passed to Shizuku beyond what is necessary to query and manage local Bluetooth connections. Shizuku operates entirely on-device.

## Support requests

If you contact support from the app's Support tab and choose to attach diagnostics, your email app sends a text file to the developer. It contains Bluetooth device names (MAC addresses are masked), your phone model and software versions, your BT Priority settings, and the app's diagnostic log. Nothing is sent unless you press send in your email app. The developer uses this information only to answer your request.

## No third-party SDKs

The app contains no advertising SDKs, analytics SDKs, or crash reporting services.

## Contact

If you have questions about this policy, contact: [support@zerolabs.fyi](mailto:support@zerolabs.fyi)
