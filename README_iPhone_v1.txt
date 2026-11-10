TUK DRIVER — SRI LANKA
iPhone Edition v1 — Mobile Foundation

Based on: v51 Cartoon World
Original archive: tuk_driver_sri_lanka_v51_cartoon_world.zip
The original v51 archive is not modified.

This is a separate mobile development branch.

Included in iPhone v1:
- Responsive layouts for portrait and landscape screens.
- Safe-area insets for iPhone display cutouts and the Home indicator.
- Touch buttons remain visible on narrow and wide screens.
- Swipe gestures on the game canvas:
  - left/right: change lane
  - swipe up: jump
  - swipe down: crouch
- Pointer Events replace the previous touch-only swipe listeners.
- Mobile renderer pixel ratio capped at 1.35 to reduce GPU load.
- Resize handling for browser viewport changes.

Not included yet:
- PWA manifest, service worker, offline cache and Home Screen installation.
- Bundled Three.js library; the game currently loads Three.js from jsDelivr and needs an internet connection.
- Real-device iPhone Safari validation.

Validation performed:
- All three inline JavaScript blocks pass Node.js syntax checking.
- Static checks confirm portrait/landscape CSS, safe-area support and Pointer Events.
- A real browser launch and real iPhone test have not been performed.

Next branch release: iPhone v2 — performance and Safari lifecycle/audio testing.
