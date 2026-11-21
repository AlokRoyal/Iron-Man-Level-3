# Iron Man — Level 3

![JavaScript](https://img.shields.io/badge/JavaScript-p5.js-FB7D24?logo=p5dotjs&logoColor=white)
![Game](https://img.shields.io/badge/type-browser%20prototype-4C8EDA)

A browser game prototype that continues the Iron Man platform mechanics. Move across a scrolling background, land on falling bricks, and collect diamonds to increase the on-screen score.

## Controls and objective

Use the left and right arrow keys to move; press the up arrow to jump. Collect diamonds and avoid falling out of the playable area while navigating the generated platforms.

## How it works

sketch.js loads background, character, brick, and diamond images from images/. It creates sprite groups, updates movement and gravity in the frame loop, checks collisions, generates objects at intervals, and renders the score. Canvas dimensions and gameplay values are defined in the sketch.

## Architecture

Keyboard input → player movement and gravity → platform/diamond generation → collision and score handling → canvas rendering

## Start locally

Open index.html in a browser with images/, lib/, and CSS/ present. No package manager or build process is configured. Use a local static server if local asset loading is restricted.

## Project layout

- index.html — browser entry point
- sketch.js — gameplay logic
- images/ — local game art
- lib/ — p5.js and p5.play
- CSS/ — stylesheet

## Limitations

Game state is in-memory only. There is no saved score, backend, game-over flow, or automated tests.