# Last Signal

**A narrated, interactive story about the machines NASA left behind.**

NASA Space Apps Challenge 2026 · Challenge: *Abandoned but not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars*

**Watch it live:** https://lilithamhle.github.io/last-signal/

*(Open it in Chrome or Edge, click "Begin with sound", and let the story play.)*

---

## About

For more than fifty years, NASA has left robots, landers and probes on the Moon, on Mars and between the stars. Most people only hear about the missions that are still running.

**Last Signal** tells the stories of the ones that went quiet. It plays like a short documentary in your browser: one machine at a time, from its mission to its final silence, with real NASA imagery, a narrator and music that follows the feeling of the story.

It opens with a question, "What happens to a machine when its mission ends?", and closes with the answer: they may look abandoned, but they are not forgotten.

## The machines in the story

- **Apollo 11 descent stage** and the other equipment left on the Moon
- **Viking 1**: the first U.S. lander to work on Mars
- **Sojourner, Spirit and Opportunity**: rovers built for days that lasted years
- **Ingenuity**: the first aircraft on another world
- **Kepler**: the telescope that found over 2,600 planets
- **NEAR Shoemaker**: never built to land, and landed on an asteroid
- **Pioneer 10**: still travelling beyond the planets

## Features

- **One-page story, no scrolling.** Lines appear one at a time with subtitles, like a film.
- **Real NASA images** for each machine, with a slow camera push-in for depth.
- **Narration that changes tone.** Celebratory for machines that beat the odds, slower and quieter for the ones that went silent.
- **Music generated live in the browser** (Web Audio API). It changes mood with each scene and softens whenever the narrator speaks.
- **Live "silence clocks"** that count the exact time since each machine last answered.
- **Controls:** Pause/Play, Sound on/off, Narrate on/off, a progress bar to jump between scenes, and click, tap, space or arrow keys to continue.

## How to use it

1. Open the link above in a modern browser.
2. Choose **Begin with sound** (music and narration) or **Begin silently**.
3. Let the story play, or click, tap or press space to move on.

Browsers only allow sound after you click, and the narrator uses your device's built-in voice, so how it sounds depends on your device. Microsoft Edge usually has the most natural voices.

## Run it on your own computer

No installation is needed. Download or clone this repository and open `index.html` in your browser.

## Built with

- HTML, CSS and JavaScript (no frameworks, no backend)
- Web Audio API for the generated music
- Web Speech API for the narration
- Hosted on GitHub Pages

## Project structure

```
index.html    the whole experience (story, design, music and narration)
media/        NASA images used as scene backgrounds
```

## Credits and sources

- Images courtesy of NASA (images.nasa.gov and science.nasa.gov).
- Facts are based on NASA mission pages (nssdc.gsfc.nasa.gov and science.nasa.gov).
- This project is not endorsed by NASA.

## Team

**Team Supernovas**: Lilitha Mhle
