# Sony-WH-1000XM5
Equalizer preset for Sony WH-1000XM5


## Precondition

### Internal Equalizer

Create a Equalizer in the App for the WH-1000XM5:

<img src="HC2xyMQ.png" alt="App Equalizer Settings" height="600"/>

[Source](https://www.reddit.com/r/SonyHeadphones/comments/14plfz0/wh1000xm5_a_guide_for_maximizing_audio_quality/)

### Programs

You need [EasyEffects](https://github.com/wwmm/easyeffects) to load the equalizer settings file.

## Versions

#### _Clear_

Open sound with high brights and deep bass down to bass woofer level.

Works best for natural recorded music without much editing, movies without many "sound effects" and similar.

#### _Balanced_

Open sound with high brights with a more balanced bass response.

Works best for semi-natural recorded music, where "bass enhancements" took place, or heavy compression was used. Works with some movies, if not too much bass effects were used.

#### _Universal_

Muted brights, with lower bass response and muted lower mids.

Works best for music which was heavily edited, like Agrotech, EDM, Pop Music, Hip-Hop and Movies with heavy soundeffects, where the bassline would just drown out the details otherwise. In short it's more for an easy listening experince where the sound editors expected bad playback devices.

## Usage

### Load the profile 

You can load the profile including the Equalizer settings from the most up-to-date version under `/profiles`.

### Additional information

Some filters are intentionally deactivated:

- `Deesser` might come handy on poor audio recordings on voice
- `Filter` comes handy on poor audio recordings with microphone rumbing
- `Noise Reduction` might come handy on *very* poor recordings of voice, where you may want to blend out background noise.

Note: The first equalizer are intentionally empty, it is used to reduce the input volume to roughtly the same amount the second EQ changes it. So it won't blow your ears out to deactivate the (real) second EQ, if you want to compare.


## Known issues

- <strike>Base is to "rumbly" on some tracks, especially Agrotech and Hip-Hop/Rap.</strike>
- <strike>Brights (around 3kHz) may sound to harsh on some tracks, especially Agrotech.</strike>
- Requires high volume listening, otherwise fill fall flat. Loudness filter on top does absolutly not help to improve this.
