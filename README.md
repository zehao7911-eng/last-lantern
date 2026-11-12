# LAST LANTERN
Original portrait 3D night-shift minibus game. English interface. Based on the supplied video's night passenger-service premise; no copied characters, models, audio or game code.

## Play
Hold the scene to accelerate. Slide horizontally to steer. Lift to brake in the wide illuminated stop. Space drives; left/right arrows steer on desktop. Avoid cones and stones. Each shift has a boarding scene, a drive, an arrival scene and a star result. Six shifts unlock in sequence, with three passenger types and three destinations. Lantern moths remove one obstacle, the baker's cake dislikes sudden high-speed steering, and the band's road song restores one heart. Six total stars unlock amber paint; reaching shift six unlocks festival lights. These cosmetics can also be unlocked by supported optional host callbacks.

## Launch / import
index.html and standalone.html each embed all rendering code and assets. No CDN, fonts, external audio or API key. ZIP has index.html at its root. WebGL is required. Original small WebAudio melody and feedback start with user gesture. Open via HTTP or import index.html into GameWave. Progress and settings use only last-lantern-v1; reloading restarts the current shift, keeping completed shifts and rewards.

## SDK
Optional window.neonlib bridge never gates standalone startup. Real shift start/end, dedicated profile save, valid confirmed like/comment rewards, one-time per-save flags, partial/late SDK detection and cleanup. Flags are browser/profile scoped, not server-verified. Official SDK document rechecked November 12, showing October 30 revision. Tests cover SDK absence, partial/late injection, rejected async methods, unsubscribe, invalid callbacks, duplicates, own/foreign saves. Actual GameWave host is not tested.

## Validation
node test.mjs — six complete simulated routes and overshoot recovery.
node sdk-test.mjs — adapter mocks.
node controller-test.mjs — actual app controller lifecycle, stop scenes, progression, pause, reload, callback rewards.
node build.cjs — regenerate self-contained entries.
Browser layout checked at 390x844. Physical iOS/Android performance is not certified. Browser automation environment throttled frames; complete runs are controller/model-tested rather than claimed as full native playthroughs.

## Assets
Original procedural models, lighting, environment and synthesized music. Three.js bundled under MIT; license in vendor/THREE-LICENSE.txt. No generated raster assets.
