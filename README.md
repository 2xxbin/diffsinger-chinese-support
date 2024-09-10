# Diffsinger Chinese Support
[README_KO.md](/README_KO.md)

The contents of the README were translated using GPT-4.

This repository proposes a new phoneme system to facilitate the use of Chinese in Diffsinger.

Please be aware that the creator is not a native speaker of Chinese, so there may be mistakes. <br />
If you need to distinguish this system from other Chinese phoneme systems, please refer to it as "2xbin-zh."

## Key Features
* It labels the compound and nasal rhymes of Chinese separately.
* It is named with a Romanized-based notation.<br />
  (To avoid phoneme collisions, some phonemes are named similarly to IPA.)

## File List
* [zhdict_2xbin.txt](/zhdict_2xbin.txt)<br />
  A dict file for training Diffsinger.
* [dsdict-zh.yaml](/dsdict-zh.yaml)<br />
  A dictionary file used after training Diffsinger, to be added to the dsdur folder.<br />
  Please set the phonemizer in OpenUtau to "DIFFS ZH."
* [phonemes.md](/phonemes.md)<br />
  An md file detailing the phoneme system.
