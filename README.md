# FF Radar — Free Fire Tactical Radar (manual input, legit tool)

A floating-bubble radar overlay for Android. You manually tap enemy positions; nothing reads game memory or files.

## Features
- Draggable floating bubble (tap to expand/collapse radar)
- Circular radar: range rings, N/S/E/W crosshair, center = you
- Tap empty area -> place enemy marker
- Tap a marker -> remove it
- Auto color by range: RED (inner ring = close), YELLOW (mid), WHITE (outer = far)
- Markers fade and auto-expire after N seconds (configurable)
- CLEAR ALL button

## Build & Run
1. Open this folder in Android Studio
2. Let Gradle sync, then Run on your device (min Android 7.0)
3. In the app: grant overlay permission -> set expiry -> Start Radar
4. A "◎" bubble appears — drag it anywhere, tap to open the radar while you play

## Notes
- Pure manual input. No game data is accessed; it is a personal tactical notepad overlay.
- To move the bubble while the radar is open, close the radar first (X CLOSE), then drag.
