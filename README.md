## Hi, I'm arcruntime

I'm a PM for AI products and build them, too. Ex-Google (developer marketing for Google Play, APAC → global). Now working on music, audio ML, and product in Tokyo.

### Primary dev project:  Lodestone

A relative-pitch ear trainer I designed and built end to end.

**[Live](https://lodestone-55o.pages.dev/app/)** · **[Source](https://github.com/arcruntime/lodestone)**

It teaches you to hear scale degrees by feel. The part I care about is underneath: it keeps three measurements separate that most trainers collapse into a frustratingly vague "sounds off."

**Roughness:** Physical beating between partials inside a critical band. Acoustic, and the same for any listener.

**Tonal pull:** Learned expectation. The app labels it that way, because there's no physical mechanism to show and pretending otherwise would be a lie.

**Harmonic fusion:** Overtone alignment, computed at runtime from equal-tempered frequencies.

There's also a waveform view that stacks the root, the interval, and their sum. Sweep from unison outward and you watch the beat envelope go from flat, to a slow shimmer, to a grind.

It's a single HTML file with Web Audio synthesis, no dependencies and no build step. Still early stages and getting tested against actual practice sessions.

### Other projects

Most of my current code is in private repos, so this profile is quieter than the work which includes:

* Pronunciation assessment integrated into an English-learning app for the Japan market
* TTS evaluation, browser Web Speech against hosted neural voices, scored on naturalness, pronunciation accuracy, and cross-device consistency
* Python and SQL analysis, METI-certified data science program

### Toolbox

`Python` · `SQL` · `Web Audio API` · `speech & TTS APIs` · `Next.js / TypeScript` · `data viz`

📍 Tokyo · 🗣️ EN / JP, JLPT N1 · 🎧 I produce and DJ, which is how Lodestone got started
