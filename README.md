# Redline Engine Lab

A browser engine simulator. Start the engine, then hold the accelerator or Space. Select an engine and shift gears using the controls.

Audio uses a procedural cylinder and exhaust model. Redlines are exaggerated for the simulator, the dashboard is conceptual, and the sounds are not calibrated recordings of the named cars.

## Audio generator

The audio worklet in `index.html` is adapted from [engine-sound-generator](https://github.com/Antonio-R1/engine-sound-generator) by Antonio-R1, Copyright (c) 2021-2022, licensed under the MIT License. The full license is included in `index.html` next to the source.

The `audio` folder contains recordings retained from earlier previews; the current simulator does not use them. Their original licenses and credits remain in `audio/CREDITS.md` and the repository history.

## Audio credits

- `audio/v8-hotrod.mp3`: Ears68, [Hot-Rod V-8](https://freesound.org/people/Ears68/sounds/144454/), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Playback speed and loop points adjusted.
- `audio/v8-real.mp3`: overmedium, [v8 engine rev](https://freesound.org/people/overmedium/sounds/651534/), CC0. Playback speed and loop points adjusted.
- `audio/lfa.ogg`: Altair78, [Lexus LFA revving](https://commons.wikimedia.org/wiki/File:Lexus_LFA_revving_1LR-GUE_(2009).ogg), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Playback speed and loop points adjusted.
- `audio/ferrari.flac`: CarSpotter, [Ferrari 599 GTB](https://commons.wikimedia.org/wiki/File:Ferrari_599_GTB_Fiorano_-_engine_and_exhaust_sound_(Flickr_3087503901).flac), [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/). Playback speed and loop points adjusted.

