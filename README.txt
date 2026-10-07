LANCE PHOTO v0.6 — RAW BETA

CONSOLIDATED BUILD
- Sony ARW / camera RAW file picker support.
- Browser-side LibRaw WASM decoding (real RAW decode; no embedded-JPEG fallback).
- Camera WB / camera matrix / highlight-preserving RAW development settings.
- File info display: filename, type, dimensions, size, camera metadata when available.
- Exact numeric entry repaired: click number, type value, Enter.
- Universal double-click slider = neutral 0.
- Universal triple-click slider = current preset/baseline.
- Quick Looks now stay highlighted.
- Clean / Portrait / Crisp / Moody / Social are mutually exclusive.
- B&W is an independent modifier and can be combined with a Quick Look.
- Tone Curve active button highlighting; Soft S reduced in strength.
- Smoother HSL color-range weighting.
- Slider redraws scheduled with requestAnimationFrame for better responsiveness.
- Desktop Chat capture now tries clipboard first; mobile retains native share fallback.
- Existing Fit / 100% / collapsible filmstrip / Before / Export retained.

IMPORTANT RAW NOTE
This beta performs genuine LibRaw decoding in the browser. The RAW source remains loaded in memory while the editor is open. The current visible editing engine works on the developed RGB render; a future milestone can move the entire adjustment pipeline to higher-bit-depth/GPU processing.

UPLOAD ALL 7 FILES TO THE ROOT OF THE EXISTING lance-photo GITHUB REPOSITORY, REPLACING THE OLD FILES, THEN COMMIT.
