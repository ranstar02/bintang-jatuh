# Bintang Jatuh — tangkap bintangnya, hindari batunya!

[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)

A tiny browser arcade game built by an AI agent from **one prompt** — for the
make.fun bounty "The agent builds a game from one prompt".

Move the basket left/right with arrow keys or mouse. Catch falling stars for
+10 points each; catching a rock costs a life. 3 lives, speed rises with
your score. Game over screen shows your final score — press R to play again.

## The one prompt

> Build a tiny browser arcade game in a single HTML file called index.html:
> "Bintang Jatuh" (Falling Stars). A basket at the bottom moves left/right
> with arrow keys or mouse. Stars fall from the sky — catch one for +10
> points. Rocks also fall — catching one costs a life. You have 3 lives.
> Speed increases as your score grows. Canvas 2D, dark night-sky background
> with twinkling stars, all code original, no external assets or libraries.
> Show score and lives on screen. Game over screen shows final score and
> "Press R to play again". Add a tiny WebAudio beep on catch.

See `prompt.md` for the exact prompt and `build.log` for the real build log.

## Run it

```sh
# just open index.html in a browser, or serve it:
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

No build step, no dependencies, no external assets — pure HTML + Canvas 2D.

## The video

`bintang-jatuh-video.mp4` (46s) shows the prompt, the agent's real build
log, and real gameplay — ending on the game running. It was posted on X
as the bounty entry (link below once live).

## License

MIT — see LICENSE.
