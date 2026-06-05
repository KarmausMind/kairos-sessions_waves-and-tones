# kairos-sessions_waves-and-tones

A minimalist browser-based soundscape prototype designed around quiet interaction, generative tones, visual rhythm, and session-based presence.

This is an experimental creative technology artifact. It is not a medical device, clinical treatment, or substitute for mental health care.

---

## What it is

A single-file HTML experience that combines:

- **Generative audio** — four independent voices (ring tone, bass ground, destello, tine) with psychoacoustic LFO breathing and micro-panning
- **Canvas animation** — a sovereign particle ring with temporal variation across four session phases, and firework actor for visual rhythm
- **Session-based interaction** — 3 to 50 minute sessions with choreographed visual transitions and ambient field evolution

Built entirely with vanilla HTML, CSS, JavaScript, canvas animation, and the Web Audio API. No dependencies. No frameworks. Single file.

---

## How to use

Open `index.html` in any modern browser. Safari, Chrome, Firefox supported.

Select a session duration. Press **Begin Session**. Use headphones for the full spatial audio experience.

---

## Technical

- Web Audio API (oscillators, compressor, LFO, wave shaper)
- Canvas 2D (TypedArray particle pools, alpha batching, dynamic frame cap)
- State machine (IDLE → ACTIVE → PAUSED → ENDING)
- Temporal variation engine (four-phase session arc)
- Accessible: `aria-live`, `role="button"`, `prefers-reduced-motion`, safe-area insets

---

## Author

**Manuel Acosta**  
LMHC · Miami, Florida  
[KarmausMind](https://x.com/KarmausMind)

---

*Prototype. Not a clinical tool. Not a medical device.*
