# Formulas

_BPM to wavetable frequency_

Get the frequency of a wavetable such that its values change `bpm` times per minute

```
freq = bpm / (60 * wavetable-length)
```

_Note to frequency_

```
freq = pitch * 2^(interval / 12)
```

where `interval` is the distance between the desired note and `pitch`.
