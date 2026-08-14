# SPILLWAY

A rubber duck derby — eighty ducks, one river, no engines.

Live: https://spillway-tawny.vercel.app

## Credits

- Music: "Jazz / Pop" by Alex McCulloch — CC0 / Public Domain, via
  [OpenGameArt](https://opengameart.org/content/jazz-pop). Thanks Alex!
  (his music blog: linked from the OpenGameArt page)
- Everything else (code, art, sound effects) is generated in-file — the
  sfx are synthesized WebAudio, the art is procedural Three.js.

## Dev

Static single file. Serve locally:

```
python -m http.server 5805
```

Headless hooks: `SPILLWAY.start()`, `SPILLWAY.sim(seconds)`, `SPILLWAY.state()`, `SPILLWAY.ducks`, `SPILLWAY.G`.
