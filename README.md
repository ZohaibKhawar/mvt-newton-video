# MVT and Newton's Method

An interactive video lesson on two week-7 calculus topics: the Mean Value Theorem and Newton's Method.

**[Watch the lesson](https://zohaibkhawar.github.io/mvt-newton-video/)**

- About 6 minutes, in 11 chapters, with graphs that draw themselves on graph paper
- Captions are always on, with optional narration from your browser's built-in voice
- Play, pause, seek, chapter jumps, and speeds from 0.75× to 1.5×
- It stops three times for you to try it: drag a tangent until it matches the secant, take one Newton step for ∛10, and answer a midterm-style MVT question
- A formula card and the full transcript sit below the player
- Light and dark themes, and it works on a phone

## Chapters

1. Start
2. A road trip: average speed and the speedometer
3. The theorem: two conditions and one promise
4. Finding c: a worked example
5. Your turn: find c
6. When MVT fails: a corner breaks the theorem
7. Newton's Method: sliding down tangent lines to a root
8. The formula: where x<sub>n+1</sub> = x<sub>n</sub> − f(x<sub>n</sub>)/f′(x<sub>n</sub>) comes from
9. Your turn: one Newton step
10. When Newton fails: flat tangents and bad first guesses
11. Recap and quiz

## Run it locally

It's one HTML file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 5330
```

Then open http://localhost:5330.

## How it's built

Plain HTML, CSS and JavaScript. The animation is drawn on a canvas from a timeline of scenes, and each caption line is one beat of a scene. Narration uses the Web Speech API, and the clock waits for each line to finish speaking. Fonts come from Google Fonts.

## License

MIT
