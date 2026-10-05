# Hi, I'm Kelly

I build small, opinionated tools for music, audio, and language learning, and I use them to practise the product calls that decide whether a clever system is worth using.

Before this I did product marketing at Google, on developer and consumer growth for Google Play across APAC and global teams. Since then I've done the Le Wagon Tokyo AI/data science bootcamp and turned it into hands-on building: Web Audio synthesis, speech and TTS pipelines, rule engines, and the evaluation work that tells you whether any of it is right.

**What I'm looking for:** product roles in AI, audio, music, learning, or creative tools, where I'm technical enough to prototype and evaluate and product-minded enough to decide what ships.

## What I'm building

**[Cratewise](https://cratewise.pages.dev)**: library health checks and situation-aware crate building for rekordbox DJs.
It flags the gaps that quietly wreck a set (missing energy ratings, no key analysis, thin cue points, off-taxonomy genres, duplicates) and tracks what changed between scans. The builder takes a specific night and room and generates a bucketed contingency crate (starters, anchors, momentum, peak, resets) that you pin, swap, and export back as rekordbox XML or M3U8. It never writes to your library, and the rules do the real work; the optional AI layer can be switched off entirely. Tuned against my own 377-track working library before anything else.

**Lodestone**: relative-pitch ear training that explains itself.
It keeps three things apart that most trainers collapse into "sounds off": *roughness* (physical beating between overtones), *tonal pull* (learned expectation, labelled as such, not presented as acoustics), and *fusion* (overtone alignment computed from real frequencies). Drill, Study, and Progress modes work end to end, with an invisible spaced-repetition scheduler and a 12×12 confusion matrix. The colour palette encodes circle-of-fifths distance and stays readable with red-green colour blindness. I'm keeping it private while the sound design and learning flow catch up to the bar. Next is audio ML: sung-response pitch tracking and melody extraction from real recordings.

**Brispi (ブリスピ)**: a Japanese-learning app for advanced learners who are past textbook curricula.
It has fast dictionary lookup, personal study sets built from small reusable vocab domains, JLPT-range filtering that hides what you already know, and pitch accent taught directly. My current focus is TTS accuracy. Cloud voices guess the pitch accent of bare words and sometimes guess wrong (観光 comes out atamadaka instead of heiban), so I'm prototyping accent-marked synthesis through Amazon Polly and Google Cloud TTS, driven by verified per-word pitch data instead of the engine's guess.

The repos are private while I get them ready for review. I'd rather show fewer projects with clear demos, honest limitations, and the product reasoning written down than leave half-finished experiments on the front page.

## How I work

- **Separate what's measured from what's assumed.** If a tool can't know something, it says so instead of guessing.
- **Validate on real use first.** A real library, real practice sessions, real learners (me first), then generalise.
- **Write the decision down.** Each project keeps a running product log and short reports that put the recommendation first.
- **Ship the cheap version.** Single-file builds and no backend until one is needed. Go web-first and let retention earn the native app.

## What I bring

- Positioning, user insight, and launch judgment from Google PMM work.
- Python, SQL, and ML/data science training, now applied to evaluation and audio.
- Prototyping across Web Audio, speech/TTS APIs, TypeScript, and React.
- A musician's and DJ's ear for audio quality and interaction feel, and fluency in Japanese for building for the Japan market.

## Toolbox

`Python` · `SQL` · `TypeScript` · `React` · `Vite` · `Web Audio API` · `speech & TTS APIs (Azure, Polly, Google)` · `Playwright` · `data visualization`

Tokyo · English / Japanese, JLPT N1 · music production and DJing
