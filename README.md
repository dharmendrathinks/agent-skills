# Tap the Alien — agent skills demo

This repository accompanies a YouTube walkthrough of turning generated game art into a small browser game and adapting a local Prototype skill. It is a reference project for the video, not a packaged game or service.

## Play the game

Clone or download this repository, then open [`output/imagegen/tap-the-alien/prototype.html`](output/imagegen/tap-the-alien/prototype.html) in a browser. Keep the two PNG files in the same directory as the HTML file. There is no build step, dependency install, account, or backend.

Tap the alien as it moves to random positions. Each tap scores one point. A round lasts 30 seconds; a score of **2 or more** unlocks the Cosmic Catcher achievement at the end. Use **Play again** to restart.

## What's in the repository

| Path | Contents |
| --- | --- |
| [`output/imagegen/tap-the-alien/`](output/imagegen/tap-the-alien/) | The playable HTML prototype, portrait space background, and transparent alien character. |
| [`skills/prototype/`](skills/prototype/) | The Prototype skill used for the workflow, with a local timed-game outcome rule in `LOGIC.md`. |

The game stores score and timer state only in the browser while a round is running. It does not send gameplay data anywhere.

## About the Prototype skill

The skill began as [Matt Pocock's Prototype skill](https://github.com/mattpocock/skills/tree/main/skills/engineering/prototype). This copy adds guidance for the Tap the Alien achievement threshold. To use it as a local Codex skill, place `skills/prototype` in your Codex skills directory, reviewing any existing `prototype` folder before replacing it.

## Project status

This repository is published as a companion to the video. There is no contribution process planned.

For security findings, use the private reporting instructions in [SECURITY.md](SECURITY.md). Public discussions are covered by the [Code of Conduct](CODE_OF_CONDUCT.md).

## License and attribution

The original game, generated artwork, and repository documentation are licensed under [Apache License 2.0](LICENSE). The copied Prototype skill retains its upstream [MIT license](skills/prototype/LICENSE). See [NOTICE](NOTICE) for attribution and the local modification.
