---
layout: ../../layouts/ProjectLayout.astro

title: Confetris
githubURL: https://github.com/AlexDuchnowski/confetris
tags: ["Interactive", "Python"]
description: A configurable version of Tetris.
---

<style>
    iframe {
        width: 100%;
        aspect-ratio: 75/77;
    }
</style>

It was a random Saturday, and I decided to program Tetris in Python for fun. As someone who has played his fair share of the game, I thought that I was familiar with all the mechanics, but as I implemented more and more of it, I discovered more and more design choices that go into the design of Tetris (the dimensions of the playfield, the number of visible next pieces, the color scheme, etc.). Also, while I had set out to emulate the classic NES version of Tetris, I realized that there were some features and mechanics in other versions of the game which I thought improved the experience, and I decided to add some of those too.

Eventually, I decided to allow the player to make these design choices themselves, revealing them as configuration settings that could be modified, and Confetris (*conf*igurable T*etris*) turned into a reality. I may return to this project to add even more customization options, but for now, I hope that it will bring some joy and surprise to those who give it a try.

To play the game, you can click the "Ready to start !" text below and then interact using your keyboard (the game is currently not playable on mobile devices). The game is also available on [itch.io](https://xenonhawk.itch.io/confetris).

<iframe title="Confetris Game" frameborder="0" src="https://itch.io/embed/3797181" allowfullscreen=""><a href="https://alexduchnowski.itch.io/confetris">CONFETRIS by AlexDuchnowski</a></iframe>

The game is written in Python and uses the [Pygame](https://www.pygame.org) library. The code is available on [GitHub](https://github.com/AlexDuchnowski/confetris).
