# voice-ktn-data

Canadian English speech database to build a [MaryTTS](http://mary.dfki.de/) voice. The database contains 612 sentences from the [Festvox CMU_ARCTIC](http://festvox.org/cmu_arctic/cmuarctic.data) prompt list. It was recorded in 2017 at Saarland University by ktn.

## Components

The audio data is released as a 48 kHz / 16 bit [FLAC](https://xiph.org/flac/) file.

The text data is provided threefold:

- a chronological [Praat](http://www.fon.hum.uva.nl/praat/) TextGrid, which contains three tiers:
    - **labels-tier**: CMU_ARCTIC prompt labels, e.g.:
        - arctic_a0001
    - **sentences-tier**: CMU_ARCTIC prompt sentences, e.g.:
        - It drowned all sound that brute agony and death may have made
    - **comments-tier**: CMU_ARCTIC prompt labels of prompts that have been excluded
    
- a txt-file for each CMU_ARCTIC prompt
    - **name**: CMU_ARCTIC prompt label
    - **content**: CMU_ARCTIC prompt sentence
    
- a chronological [Praat](http://www.fon.hum.uva.nl/praat/) TextGrid for each CMU_ARCTIC prompt
    - **name**: CMU_ARCTIC prompt label
    - **content**: CMU_ARCTIC prompt sentence in SAMPA phonetic transcription as force aligend by [WebMAUS](http://clarin.phonetik.uni-muenchen.de/BASWebServices/#/services/WebMAUSMultiple)

## Voicebuilding

To build the voice see [voice-ktn-build](http://github.com/ravehe/voice-ktn-build).

## License

[![Creative Commons License](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nd.svg)](http://creativecommons.org/licenses/by-nd/4.0/legalcode)

This database is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nd/4.0/legalcode).
