---
layout: default
title: Open-source License Inventory
---

# ShooterLog Open-source Licenses

Generated: 2026-03-06

This project uses third-party open-source software.

## Runtime dependency license summary

`npx license-checker --production --summary` on 2026-03-04 returned:

- MIT: 575
- ISC: 41
- BSD-3-Clause: 16
- BSD-2-Clause: 15
- Apache-2.0: 12
- BlueOak-1.0.0: 9
- 0BSD: 3
- Unlicense: 2
- MPL-2.0: 2
- (MIT OR CC0-1.0): 2
- Python-2.0: 1
- CC-BY-4.0: 1
- CC0-1.0: 1
- (BSD-3-Clause OR GPL-2.0): 1
- (MIT AND Zlib): 1
- Apache 2.0: 1
- (BSD-2-Clause OR MIT OR Apache-2.0): 1
- UNLICENSED: 1

## Direct runtime dependencies (from `package.json`)

All direct runtime dependencies currently declare `MIT` license:

- @react-native-async-storage/async-storage
- @react-native-community/datetimepicker
- base64-js
- crypto-js
- expo
- expo-constants
- expo-crypto
- expo-document-picker
- expo-file-system
- expo-image-manipulator
- expo-image-picker
- expo-linking
- expo-router
- expo-secure-store
- expo-sharing
- expo-status-bar
- jszip
- pdf-lib
- react
- react-dom
- react-native
- react-native-gesture-handler
- react-native-reanimated
- react-native-safe-area-context
- react-native-screens
- react-native-svg
- react-native-web
- react-native-worklets
- zod

## Compliance note

For store release, keep a reproducible process to regenerate license notices per build.
Recommended:

1. Run `npx license-checker --production --summary`.
2. Run `npx license-checker --production --json > docs/legal/licenses-production.json`.
3. Include required attribution notices in app documentation and release artifacts.
