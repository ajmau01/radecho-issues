# RadEcho — Notes & Write-ups

Deeper write-ups on specific features and changes. Not a replacement for the issue history — just extra background for anyone who wants the "why," not just the "what."

## Reference

Evergreen explainers — accurate regardless of when you're reading them.

### [Classic vs. Native Rendering](https://claude.ai/code/artifact/1160222a-903a-4a0e-9c29-c1da247bc2d9)

Why the two **Style** options in the viewer (Classic / Native) produce different-looking pictures from the exact same radar data. Covers the polar geometry both styles share (every reading is placed at its true position relative to the tower either way), where they actually diverge — nearest-match sampling vs. true wedge shapes — the trig behind gate placement, and a live side-by-side capture from a real storm.

## What's New

Point-in-time snapshots of what shipped in a given session — written once and not kept up to date, so treat the date as "accurate as of," not "current state."

### 2026-07-22 — [RhoHV Filter, Save/Export, Toolbar Redesign](https://claude.ai/code/artifact/fb2c89ce-2f33-4faa-8af5-01d9246cf456)

Two friend-requested features shipped together, plus a control-bar cleanup: a **Filter non-weather** toggle that reveals what RadEcho normally strips out (birds, insects, ground clutter — and genuine signal like wildfire smoke), one-click **Save image / Copy image / Save animated GIF**, and a reorganized toolbar grouped by Location/Display instead of one flat row. Also covers two real bugs found and fixed along the way (a stale-render toggle bug and a GIF export that could hang in a backgrounded tab).
