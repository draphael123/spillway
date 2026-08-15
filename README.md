# SPILLWAY

A rubber duck derby — eighty ducks, one river, no engines.

Live: https://spillway-tawny.vercel.app

## Credits

All music and ambience via [OpenGameArt](https://opengameart.org) — thank you all!

- Spillway Run theme: "Jazz / Pop" by Alex McCulloch — CC0
  (https://opengameart.org/content/jazz-pop)
- Millrace theme: "BanjoSomething" by GP-0 — CC0
  (https://opengameart.org/content/banjosomething)
- Undergrove theme: "Mysterious Ambience (song21)" by cynicmusic / pixelsphere.org — CC0
  (https://opengameart.org/content/mysterious-ambience-song21)
- Canopy Run theme: "Happy Adventure Loop" by tinyworlds — CC0
  (https://opengameart.org/content/happy-adventure-loop)
- Menu theme: "Happy Clappy Loop" by Owlish Media — CC0
  (https://opengameart.org/content/happy-clappy-loop)
- Grandstand crowd + finish cheer: "Free Crowd Cheering Sounds" by Gregor Quendel — CC-BY 3.0
  (https://opengameart.org/content/free-crowd-cheering-sounds)
- Champion fireworks: "Fireworks with applause" by almitory — CC0
  (https://opengameart.org/content/fireworks-with-applause-happy-people)
- Millrace machinery: "Generator Loop" by ycbcr — CC0
  (https://opengameart.org/content/generator-loop)
- Undergrove cave drips: "Dripping Water Loop" by qubodup — CC0
  (https://opengameart.org/content/dripping-water-loop)
- Everything else (code, art, remaining sound effects) is generated in-file —
  the sfx are synthesized WebAudio, the art is procedural Three.js.

## Dev

Static single file. Serve locally:

```
python -m http.server 5805
```

Headless hooks: `SPILLWAY.start()`, `SPILLWAY.sim(seconds)`, `SPILLWAY.state()`, `SPILLWAY.ducks`, `SPILLWAY.G`.
