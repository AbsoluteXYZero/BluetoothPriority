# Privacy Policy — Bluetooth Priority

*Last updated: March 2, 2026*

Bluetooth Priority ("the app") is a Bluetooth audio management utility for Android. This policy describes how the app handles information.

## No data is collected or transmitted

The app does not collect, store, transmit, or share any personal information, usage data, analytics, or device identifiers with the developer or any third party. All data the app generates (event logs, settings, device preferences) is stored exclusively on your device and never leaves it.

## Bluetooth permissions

The app requests Bluetooth permissions (`BLUETOOTH_CONNECT`, `BLUETOOTH_SCAN`) solely to detect connected audio devices and enforce your configured audio routing policy. Device names and MAC addresses are used only in memory at runtime and in the on-device event log. They are never transmitted off-device.

## Shizuku

The app optionally uses Shizuku, a third-party privilege manager, to access additional Bluetooth APIs. No data is passed to Shizuku beyond what is necessary to query and manage local Bluetooth connections. Shizuku operates entirely on-device.

## No third-party SDKs

The app contains no advertising SDKs, analytics SDKs, or crash reporting services.

## Contact

If you have questions about this policy, contact: [bluetoothpriority@mail.absolutezero.fyi](mailto:bluetoothpriority@mail.absolutezero.fyi)
