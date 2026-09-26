# Rock Chord Progression Ear Trainer

A standalone, zero-dependency, 100% client-side web application for rock and blues-rock chord progression ear training. Synthesizes rock guitar, bass, and drums in real time using the Web Audio API and quizzes players on chord progressions using Roman numerals.

## 🎸 Features
- **Real-Time DSP Synthesis (Web Audio API)**:
  - Multi-oscillator detuned sawtooth guitar with asymmetric tube saturation waveshaping and 4.2 kHz 12" speaker cab simulation.
  - Sub-octave bass engine tracking roots and inverted slash chords.
  - Synthesized dynamic kick, snare, and hi-hat rhythm generator.
  - Selectable amp overdrive presets (Clean Tweed, Edge of Breakup, Plexi Crunch, High-Gain Lead).
- **Chord Progression Ear Training Quiz Engine**:
  - 21 curated rock & blues-rock chord progressions (Mixolydian anthems, Andalusian descents, Dorian jams, Grunge shifts, 50s doo-wop, Pop-punk axis, etc.).
  - Quality-neutral power chord grading (accepts both major and minor degree roots like `♭VII`/`♭vii`, `IV`/`iv`).
  - Inversion engine: Root position only, Random inversions, or Always invert (slash bass and inverted 4ths).
  - Strict Blind Mode vs. Relaxed Mode.
  - Continuous chord progression loop mode with instant start/stop controls.
  - Comprehensive theory cards revealing modal context and famous reference songs.
- **Rock Chord Lab / Sandbox**:
  - Interactive audition pads across 5 rock keys (A, E, D, G, C).
  - Scratchpad chain builder with continuous looping and synchronized visual step highlighting.
- **100% Offline Analytics & Persistence**:
  - Backward-compatible versioned storage tracking accuracy %, streaks, degree mastery progress bars, and ear confusion blindspots.
  - JSON export/import data portability.
- **Zero Dependencies**: 100% client-side single file, runs offline on any mobile or desktop browser.

## 🚀 Getting Started
Open `index.html` directly in any modern browser (Chrome, Firefox, Safari, Edge) or host it via GitHub Pages.
