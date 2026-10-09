<div align="center">

  <img src="./../.github/logo/cr-logo-256x256.png" alt="Calistadalane Records">

  <hr>

  <h1>Pedalboard</h1>

</div>

| CONTENTS |
|---|
| [Guitar](#guitar) |
| [Bass](#bass) |

# Guitar

```mermaid
flowchart LR
    %% Components
    GuitarOutput@{shape: rounded, label: "Guitar\noutput"}
    DonnerDt1@{shape: rounded, label: "Donner\nDT-1"}
    EnoExEq7@{shape: rounded, label: "ENO EX\nEQ7"}
    SonicakeRudeMouse@{shape: rounded, label: "Sonicake\nRude Mouse"}
    GreenRussian@{shape: rounded, label: "Electro-Harmonix\nBigg Muff Pi\nGreenRussian"}
    SonicakeNoiseWiper@{shape: rounded, label: "Sonicake\nNoise Wiper"}
    BossRC1@{shape: rounded, label: "Boss RC-1\nLoop Station\nInput A"}
    FenderMustang@{shape: rounded, label: "Fender\nMustang LT25"}
    %% Layout
    GuitarOutput --> DonnerDt1 --> EnoExEq7 --> SonicakeRudeMouse --> GreenRussian --> SonicakeNoiseWiper --> BossRC1 --> FenderMustang
    %% Styles
```

## ENO EX EQ7

| Band    | Doom      | Stoner | Sludge | Weird |
|---------|:---------:|:------:|:------:|:------|
| 100 Hz  | -3 dB     | -2     | -3     | -4    |
| 200 Hz  | -2 dB     | -1     | -2     | -3    |
| 400 Hz  | +1 dB     | +1     | +1     | +1    |
| 800 Hz  | +2 dB     | +1     | +2     | +3    |
| 1.6 kHz | +1 dB     | 0      | +1     | +2    |
| 3.2 kHz | 0 dB      | -1     | 0      | +1    |
| 6.4 kHz | -2 dB     | -2     | -2     | +1    | 
| Level   | 0 / unity |        |        |       |

<!--
Reduce it 800 Hz to +1 or 0 if it's too nasally.
-->

## Sonicake Rude Mouse

| Setting | Doom      | Stoner | Sludge  | Weird      |
|---------|:---------:|:------:|:-------:|:----------:|
| Mode    | Classic   | Off    | Classic | Hot        |
| Gain    | 8:30-9:00 | Off    | 9:00    | 9:00-10:00 |
| Filter  | 11:00     | Off    | 11:00   | 11:00      |
| Level   | 1:30-2:00 | Off    | 2:00    | 1:30       |

## Big Muff Green Russian

| Setting | Doom  | Stoner | Sludge | Weird      |
|---------|:-----:|:------:|:------:|:----------:|
| Volume  | 12:30 | 12:30  | 12:30  | 1:00       |
| Tone    | 10:00 | 9:30   | 10:30  | 10:30      |
| Sustain | 2:30  | 3:00   | 3:00   | 3:00-3:30  |

<!--
If it sounds too bright, move tone towards 9:30.
If it sounds too muddy, move tone to 11:00-12:00.
-->

## Sonicake Noise Wiper

| Setting   | Doom   | Stoner | Sludge | Weird  |
|-----------|:------:|:------:|:------:|:------:|
| Mode      | Smooth | Smooth | Smooth | Smooth |
| Threshold | 9:30   | 9:30   | 9:30   | 9:30   |

<!--
Increase the threshold until the hiss disappears, then **back it off slightly**
-->

## Fender Mustang LT25

| Setting | Doom      | Stoner    | Sludge    | Weird     |
|---------|:---------:|:---------:|:---------:|:---------:|
| Mode    | 70's Rock | 70's Rock | 70's Rock | 70's Rock |
| Gain    | 2.5-3.5   | 2.5-3.5   | 3         | 3-4       |
| Volume  | 5         | 5         | 5         | 5         |
| Bass    | 4         | 4         | 4         | 3.5-4     |
| Middle  | 6.5-7     | 6.5-7     | 7         | 7-8       |
| Treble  | 4-4.5     | 4-4.5     | 4         | 4         |
| Reverb  | 0-1       | 0-1       | 0-1       | 0-1       |

# Bass

```mermaid
flowchart LR
    %% Components
    BassOutput@{shape: rounded, label: "Bass\noutput"}
    DonnerHarmonicSquare@{shape: rounded, label: "Donner\nHarmonic Square"}
    SonicakeFazyCream@{shape: rounded, label: "Sonicake\nFazyCream"}
    SonicakeNoiseWiper@{shape: rounded, label: "Sonicake\nNoise Wiper"}
    BossRC1@{shape: rounded, label: "Boss RC-1\nLoop Station\nInput B"}
    FenderRumble@{shape: rounded, label: "Fender\nRumble"}
    %% Layout
    BassOutput --> DonnerHarmonicSquare --> SonicakeFazyCream --> SonicakeNoiseWiper --> BossRC1 --> FenderRumble
    %% Styles
```

## Donner Harmonic Square

| Setting | Doom       | SuperDoom | Submarine |
|---------|:----------:|:---------:|:---------:|
| Mode    | Flat       | Flat      | Flat      |
| Type    | 1 Octave   | 1 Octave  | 1 Oct     |
| DRY     | 2:00       | 12:00     | 10:00     |
| WET     | 9:30-10:30 | 12:00     | 2:00      |

<!--
If the speaker struggles, reduce WET
-->

## Sonicake Fazy Cream

| Setting | Doom  | Submarine |
|---------|:-----:|:---------:|
| Level   | 12:30 | 12:30     |
| Fuzz    | 1:30  | 12:00     |
| Tone    | 10:00 | 9:30      |

## Sonicake Noise Wiper

| Setting   | Doom   | Submarine |
|-----------|:------:|:---------:|
| Mode      | Smooth | Smooth    |
| Threshold | 9:00   | 9:00      |

<!--
Increase the threshold until the hiss disappears, then **back it off slightly**.
-->

## Fender Rumble 25

| Setting   | Doom | Submarine |
|-----------|:----:|:---------:|
| Volume    | 4-5  | 4-5       |
| Bass      | 5    | 5         |
| Middle    | 6-7  | 7         |
| Treble    | 3-4  | 3         |
| Overdrive | Off  | Off       |
| Contour   | Off  | Off       |
