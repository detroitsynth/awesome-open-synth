# awesome-open-synth
#### awesome-open-synth is a collection of open source audio processing, audio synthesis, and related libraries for a number of programming languages and hardware platforms. Resources were taken from any available outlet including articles, GitHub organizations, other README files and lists, and really anything we were able to find. Special thanks to [Jon Moshier](https://github.com/jonmoshier) for the great [awesome-open-source-synths](https://github.com/jonmoshier/awesome-open-source-synths) list, and [Woyten](https://github.com/Woyten) for the great [microtonal-rust](https://github.com/Woyten/microtonal-rust) list.

#### If there's anything missing from this list that you'd like to see added, or anything on the list that you don't think should be here, please feel free to submit a pull request to add any useful tools to awesome-open-synth.

#### The current state of this list is just a starting point for mapping out this ecosystem, and clearly does not touch on every single open source audio library on GitHub, but we'll continue developing the list as more libraries are found, released, and otherwise assembled here for everyone's benefit.

## Contents

- [Arduino](#arduino)
- [C/C++)(#cc)
- [Elixir](#elixir)
- [Go](#go)
- [Hardware](#hardware)
- [JavaScript](#javascript)
- [nesC](#nesc)
- [Rust](#rust)
- [SuperCollider](#supercollider)
- [Swift](#swift)
- [Additional Resources](#additional-resources)

## Arduino
| Name                                                                       | Library Type                       | Developer                                                                                 | License | Languages    |
| :------------------------------------------------------------------------- | :--------------------------------- | :---------------------------------------------------------------------------------------- | :------ | :----------- |
| [Euclidean-sequencer](https://github.com/TomWhitwell/Euclidean-sequencer-) | Euclidean rhythm generation system | [Tom Whitwell](https://github.com/TomWhitwell) ([website](https://www.musicthing.co.uk/)) | None    | Arduino      |
| [Dodeca](https://github.com/jakplugg/Dodeca)                               | Versatile MIDI out                 | [jakplugg](https://github.com/jakplugg)                                                   | None    | Arduino, C++ |

## C/C++
| Name                                                                         | Library Type                                | Developer                                                                                             | License                  | Languages                       |
| :--------------------------------------------------------------------------- | :------------------------------------------ | :---------------------------------------------------------------------------------------------------- | :----------------------- | :------------------------------ |
| [8mu](https://github.com/TomWhitwell/8mu_Public)                             | MIDI Sequencer                              | [Tom Whitwell](https://github.com/TomWhitwell) ([website](https://www.musicthing.co.uk/))             | None listed              | C++, Svelte, TypeScript, Python |
| [airwave](https://github.com/asb2m10/airwave)                                | Wine-based VST2 plugin runner for Linux     | [Pascal Gauthier](https://github.com/asb2m10)                                                         | MIT License              | C++                             |
| [Braids](https://github.com/pichenettes/eurorack/tree/master/braids)         | Monophonic digital sound source             | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | MIT (STM32F)             | C++                             |
| [Branches](https://github.com/pichenettes/eurorack/tree/master/branches)     | Dual Bernoulli gate                         | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [Clouds](https://github.com/pichenettes/eurorack/tree/master/clouds)         | Reverb                                      | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [DelugeFirmware](https://github.com/SynthstromAudible/DelugeFirmware)        | Firmware for the popular Deluge Synthesizer | [Synthstrom Audible](https://github.com/SynthstromAudible) ([website](https://synthstrom.com/))       | GPL-3.0                  | C, C++                          |
| [Dexed](https://github.com/asb2m10/dexed)                                    | FM Synth Plugin                             | [Pascal Gauthier](https://github.com/asb2m10)                                                         | GPL-3.0                  | C++                             |
| [dr_libs](https://github.com/mackron/dr_libs/)                               | Audio Decoding                              | [Mackron](https://github.com/mackron)                                                                 | Public Domain or MIT     | C, C++                          |
| [Edges](https://github.com/pichenettes/eurorack/tree/master/edges)           | Quad Chiptune Oscillator                    | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [Elements](https://github.com/pichenettes/eurorack/tree/master/elements)     | Modal Synthesizer                           | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [FAUST](https://github.com/grame-cncm/faust)                                 | Language/DSL                                | [GRAME](https://github.com/grame-cncm)                                                                | GPL-2.0                  | C++, Faust, C                   |
| [Grids](https://github.com/pichenettes/eurorack/tree/master/grids)           | Topographic Drum Sequencer                  | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [iPlug2](https://github.com/iPlug2/iPlug2)                                   | Audio Plugin Framework                      | [iPlug2](https://github.com/iPlug2)                                                                   | Proprietary free license | C, C++, Objective C             |
| [jsusfx](https://github.com/asb2m10/jsusfx)                                  | Open source implementation of Jesusonic FX  | [Pascal Gauthier](https://github.com/asb2m10)                                                         | GPL-3.0                  | C, C++                          |
| [lmms](https://github.com/LMMS/lmms)                                         | DAW                                         | [LMMS](https://github.com/LMMS)                                                                       | GPL-2.0                  | C++, C                          |
| [MegaDirt](https://github.com/asb2m10/MegaDirt)                              | Tidal audio engine based on SuperDirt       | [Pascal Gauthier](https://github.com/asb2m10)                                                         | AGPL-3.0                 | C++                             |
| [miniaudio](https://github.com/mackron/miniaudio)                            | Audio Playback and Capture                  | [Mackron](https://github.com/mackron)                                                                 | Public Domain or MIT     | C                               |
| [Monique Monosynth](https://github.com/surge-synthesizer/monique-monosynth/) | Monosynth                                   | [Surge](https://github.com/surge-synthesizer)                                                         | GPL-3.0, MIT             | C++                             |
| [Odin2](https://github.com/TheWaveWarden/odin2)                              | synth with oscillators as a VST3 plugin     | [TheWaveWarden](https://github.com/TheWaveWarden)                                                     | GPL-3.0                  | C++, C                          |
| [orgone-accumulator](https://github.com/jakplugg/Orgone-accumulator)         | neutron sound accumulator                   | [jakplugg](https://github.com/jakplugg)                                                               | None listed              | C++                             |
| [Peaks](https://github.com/pichenettes/eurorack/tree/master/peaks)           | Envelope/LFO/Drum generator                 | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [PluginCollider](https://github.com/asb2m10/plugincollider)                  | SuperCollider as a VST3 plugin              | [Pascal Gauthier](https://github.com/asb2m10)                                                         | GPL-3.0                  | C++, SuperCollider              |
| [Radio Music](https://github.com/TomWhitwell/RadioMusic)                     | Virtual radio module for eurorack           | [Tom Whitwell](https://github.com/TomWhitwell) ([website](https://www.musicthing.co.uk/))             | None listed              | C++                             |
| [Rings](https://github.com/pichenettes/eurorack/tree/master/rings)           | Resonator                                   | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [rtaudio](https://github.com/thestk/rtaudio)                                 | Realtime audio processing                   | [STK Team](https://github.com/thestk) ([website](https://ccrma.stanford.edu/software/stk/index.html)) | Modified MIT             | C++, C, M4, Go                  |
| [rtmidi](https://github.com/thestk/rtmidi)                                   | Realtime MIDI processing                    | [STK Team](https://github.com/thestk) ([website](https://ccrma.stanford.edu/software/stk/index.html)) | Modified MIT             | C++, M4, Go, C                  |
| [Sfizz](https://github.com/sfztools/sfizz)                                   | SFZ parser and synth c++ library            | [SFZ Tools](https://github.com/sfztools)                                                              | BSD-2-Clause             | C++                             |
| [Shortcircuit XT](https://github.com/surge-synthesizer/shortcircuit-xt)      | Sampler                                     | [Surge](https://github.com/surge-synthesizer)                                                         | GPL-3.0                  | C++, Scheme                     |
| [Stochas](https://github.com/surge-synthesizer/stochas)                      | Sequencer                                   | [Surge](https://github.com/surge-synthesizer)                                                         | GPL-3.0                  | C++, C                          |
| [SuperCollider](https://github.com/supercollider)                            | Audio server, programming language, and IDE | [supercollider](https://github.com/supercollider)                                                     | GPL-3.0                  | C++, SuperCollider, C           |
| [SuperColliderAU](https://github.com/supercollider/SuperColliderAU)          | AudioUnit wrapper for SuperCollider         | [supercollider](https://github.com/supercollider)                                                     | None listed              | C++, R, C                       |
| [Surge Rack](https://github.com/surge-synthesizer/surge-rack)                | Surge XT for VCV Rack                       | [Surge](https://github.com/surge-synthesizer)                                                         | GPL-3.0                  | C++, Javascript                 |
| [Surge XT](https://github.com/surge-synthesizer/surge)                       | Hybrid Synth                                | [Surge](https://github.com/surge-synthesizer)                                                         | GPL-3.0                  | C, C++                          |
| [The Synthesis Toolkit (STK)](https://github.com/thestk/stk)                 | Signal processing and synthesis             | [STK Team](https://github.com/thestk) ([website](https://ccrma.stanford.edu/software/stk/index.html)) | Modified MIT             | C++, C, Tcl, M4                 |
| [Tides](https://github.com/pichenettes/eurorack/tree/master/tides)           | Tidal modulator                             | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |
| [VCV Rack](https://github.com/VCVRack/Rack)                                  | Virtual Eurorack Studio                     | [VCV Rack](https://github.com/VCVRack)                                                                | GPL-3.0                  | C++                             |
| [Yarns](https://github.com/pichenettes/eurorack/tree/master/yarns)           | Midi to CV interface                        | [Mutable Instruments](https://github.com/pichenettes) ([website](https://mutable-instruments.net/))   | Review repo              | C++                             |

## Elixir
| Name                                               | Library Type                 | Developer                                        | License     | Languages |
| :------------------------------------------------- | :--------------------------- | :----------------------------------------------- | :---------- | :-------- |
| [NxSignal](https://github.com/elixir-nx/nx_signal) | Digital Signal Processor     | [Numerical Elixir](https://github.com/elixir-nx) | Apache 2.0  | Elixir    |
| [Oscillixir](https://github.com/jpmec/oscillixir)  | Synthesizer with oscillators | [Josh Petitt](https://github.com/jpmec)          | None listed | Elixir    |

## Go
| Name                                                            | Library Type               | Developer                                          | License      | Languages |
| :-------------------------------------------------------------- | :------------------------- | :------------------------------------------------- | :----------- | :-------- |
| [flac](https://github.com/mewkiz/flac)                          | FLAC encoder/decoder       | [Mewkiz](https://github.com/mewkiz)                | Unilicense   | Go        |
| [gaad](https://github.com/Comcast/gaad)                         | AAC decoder                | [Comcast](https://github.com/Comcast)              | Apache-2.0   | Go        |
| [GoAudio](https://github.com/DylanMeeus/GoAudio)                | Audio Tools                | [Dylan Meeus](https://github.com/DylanMeeus)       | MIT          | Go        |
| [gosamplerate](https://github.com/dh1tw/gosamplerate)           | Bindings for libsamplerate | [Tobias Wellnitz](https://github.com/dh1tw)        | BSD-2 Clause | Go        |
| [id3v2](https://github.com/n10v/id3v2)                          | ID3 encoding/decoding      | [Albert Nigmatzianov](https://github.com/n10v)     | MIT          | Go        |
| [music-theory](https://github.com/go-music-theory/music-theory) | Music theory impementation | [Music Theory](https://github.com/go-music-theory) | GPL-3.0      | Go        |
| [oto](https://github.com/hajimehoshi/oto)                       | Audio player               | [Hajime Hoshi](https://github.com/hajimehoshi)     | Apache-2.0   | Go        |
| [portaudio](https://github.com/gordonklaus/portaudio)           | Bindings for portaudio     | [Gordon Klaus](https://github.com/gordonklaus)     | MIT          | Go        |

## Hardware
| Name                                                                                            | Library Type              | Developer                                                               | License     | Languages |
| :---------------------------------------------------------------------------------------------- | :------------------------ | :---------------------------------------------------------------------- | :---------- | :-------- |
| [Blinds](https://github.com/pichenettes/eurorack/tree/master/blinds)                            | Quad VC-P                 | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Ears](https://github.com/pichenettes/eurorack/tree/master/ears)                                | Contact Microphone        | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Edgecutter](https://github.com/ThisIsNotRocketScience/Eurorack-Modules/tree/master/Production) | Visual envelope           | [This is Not Rocket Science](https://github.com/ThisIsNotRocketScience) |             | None      |
| [Kinks](https://github.com/pichenettes/eurorack/tree/master/kinks)                              | Analog rectifier, noise   | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Klangatorium](https://github.com/hexagon5un/klangorium)                                        | Synth experiment board    | [Elliot Williams](https://github.com/hexagon5un)                        | None listed | None      |
| [Mikrophonie](https://github.com/TomWhitwell/Mikrophonie)                                       | Microphone module         | [Tom Whitwell](https://github.com/TomWhitwell)                          | None        | None      |
| [Pulses](https://github.com/TomWhitwell/Turing-Pulse-Expander)                                  | Pulse expander            | [Tom Whitwell](https://github.com/TomWhitwell)                          | None        | None      |
| [Ripples](https://github.com/pichenettes/eurorack/tree/master/ripples)                          | Multi-stage filter        | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Shelves](https://github.com/pichenettes/eurorack/tree/master/shelves)                          | EQ Filter                 | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Streams](https://github.com/pichenettes/eurorack/tree/master/streams)                          | Dual dynamics gate        | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [T_u](https://github.com/jakplugg/T_u)                                                          | Clock generator           | [jakplugg](https://github.com/jakplugg)                                 | None        | None      |
| [Triple Attenuator Mixer v2](https://github.com/ishkabbible/Triple_Attenuverter_Mixer_v2)       | Attenuators/Mixer         | [Dave Hamara](https://github.com/ishkabbible)                           | CC-BY-SA    | None      |
| [Tuesday](https://github.com/ThisIsNotRocketScience/Eurorack-Modules/tree/master/Production)    | Procedural Sequencer      | [This is Not Rocket Science](https://github.com/ThisIsNotRocketScience) |             | None      |
| [Turing Machine](https://github.com/TomWhitwell/TuringMachine)                                  | Random Loolping Sequencer | [Tom Whitwell](https://github.com/TomWhitwell)                          |             | None      |
| [uO_c](https://github.com/jakplugg/uO_c)                                                        | Polymorphic CV generator  | [jakplugg](https://github.com/jakplugg)                                 | None listed | None      |
| [Veils](https://github.com/pichenettes/eurorack/tree/master/veils)                              | Quad VCA                  | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Voltages](https://github.com/TomWhitwell/Voltages-Expander)                                    | Voltages expander         | [Tom Whitwell](https://github.com/TomWhitwell)                          | None        | None      |
| [Volts](https://github.com/TomWhitwell/Volts)                                                   | Mini voltages expander    | [Tom Whitwell](https://github.com/TomWhitwell)                          | None        | None      |
| [Waves](https://github.com/pichenettes/eurorack/tree/master/warps)                              | Waveshaper/Modulator      | [Mutable Instruments](https://github.com/pichenettes)                   | Check repo  | None      |
| [Wobbler](https://github.com/ThisIsNotRocketScience/Eurorack-Modules/tree/master/Production)    | Advanced LFO              | [This is Not Rocket Science](https://github.com/ThisIsNotRocketScience) |             | None      |

## JavaScript
| Name                                          | Library Type                            | Developer                                     | License | Languages  |
| :-------------------------------------------- | :-------------------------------------- | :-------------------------------------------- | :------ | :--------- |
| [glasgow](https://github.com/asb2m10/glasgow) | programmable note generator for Ableton | [Pascal Gauthier](https://github.com/asb2m10) | None    | JavaScript |

## nesC
| Name                                           | Library Type                                 | Developer                               | License | Languages |
| :--------------------------------------------- | :------------------------------------------- | :---------------------------------------| :------ | :-------- |
| [m-Brane](https://github.com/jakplugg/m-Brane) | Compact version of Mutable Instruments Yarns | [jakplugg](https://github.com/jakplugg) | None    | nesC      |
| [uGrids](https://github.com/jakplugg/uGrids)   | Compact version of Mutable Instruments Grids | [jakplugg](https://github.com/jakplugg) | None    | nesC      |

## Rust
| Name                                                         | Library Type                                         | Developer                                                                                | License           | Languages             |
| :----------------------------------------------------------- | :--------------------------------------------------- | :--------------------------------------------------------------------------------------- | :---------------- | :-------------------- |
| [baseplug](https://github.com/wrl/baseplug)                  | MVC Framework for rust audio plugins                 | [William Light](https://github.com/wrl)                                                  | Apache 2.0 or MIT | Rust                  |
| [baseview](https://github.com/RustAudio/baseview)            | low-level interface for audio plugin UIs             | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |
| [camilla DSP](https://github.com/HEnquist/camilladsp)        | IIR/FIR engine for crossovers, room correction, etc. | [Henrik Enquist](https://github.com/HEnquist) ([website](https://henquist.github.io/))   | GPL-3.0           | Rust                  |
| [claxon](https://github.com/ruuda/claxon)                    | FLAC decoder                                         | [Rud van Asseldonk](https://github.com/ruuda) ([website](https://ruudvanasseldonk.com/)) | Apache 2.0        | Rust                  |
| [coremidi](https://github.com/chris-zen/coremidi)            | CoreMIDI (OS X) Library                              | [Christian Zen](https://github.com/chris-zen)                                            | MIT               | Rust                  |
| [Cpal](https://github.com/rustaudio/cpal)                    | Cross-Platform Audio I/O Library                     | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |
| [creek](https://github.com/MeadowlarkDAW/creek)              | realtime disk streaming for audio IO                 | [MeadowlarkDAW](https://github.com/MeadowlarkDAW)                                        | Apache 2.0 or MIT | Rust                  |
| [dasp](https://github.com/RustAudio/dasp)                    | Digital audio signal processing                      | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |
| [druid](https://github.com/linebender/druid)                 | GUI library for Rust                                 | [linebender](https://github.com/linebender) ([website](https://linebender.org/druid/))   | Apache 2.0        | Rust                  |
| [egui](https://github.com/emilk/egui)                        | Another GUI library for Rust                         | [Emil Enerfeldt](https://github.com/emilk)                                               | Apache 2.0 or MIT | Rust                  |
| [FunDSP](https://github.com/SamiPerttu/fundsp)               | Audio Processing and Synth                           | [Sam Perttu](https://github.com/SamiPerttu)                                              | Apache 2.0 or MIT | Rust                  |
| [Glicol](https://github.com/chaosprint/glicol)               | Graph Oriented Coding Language                       | [Qichao Lan](https://github.com/chaosprint) ([website](https://glicol.org/))             |                   | Rust, JavaScript      |
| [Hexosynth](https://github.com/WeirdConstructor/HexoSynth)   | Hexagonal Modular Synth Plugin                       | [Weird Constructor](https://github.com/WeirdConstructor)                                 | GPL-3.0           | Rust                  |
| [hound](https://github.com/ruuda/hound)                      | wav encoding/decoding library                        | [Rud van Asseldonk](https://github.com/ruuda) ([website](https://ruudvanasseldonk.com/)) | Apache 2.0        | Rust                  |
| [Iced](https://github.com/iced-rs/iced)                      | GUI library                                          | [Iced-RS](https://github.com/iced-rs) ([website](https://iced.rs/))                      | MIT               | Rust                  |
| [Iced Audio](https://github.com/iced-rs/iced_audio)          | Audio-centric GUI plugins for Iced                   | [Iced-RS](https://github.com/iced-rs) ([website](https://iced.rs/))                      | MIT               | Rust                  |
| [imgui-rs](https://github.com/imgui-rs/imgui-rs)             | GUI library for Rust                                 | [imgui-rs](https://github.com/imgui-rs)                                                  | Apache 2.0 or MIT | Rust                  |
| [kiro-synth](https://github.com/chris-zen/kiro-synth)        | Modular Synth                                        | [Christian Zen](https://github.com/chris-zen)                                            | None Listed       | Rust                  |
| [lewton](https://github.com/RustAudio/lewton)                | Vorbis decoder                                       | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |
| [maschine.rs](https://github.com/wrl/maschine.rs)            | Maschine bindings for mikro mk2                      | [William Light](https://github.com/wrl)                                                  | LGPL-3.0          | Rust                  |
| [MeadowlarkDAW](https://github.com/MeadowlarkDAW/Meadowlark) | open source DAW                                      | [MeadowlarkDAW](https://github.com/MeadowlarkDAW)                                        | GPL-3.0           | Rust                  |
| [musium](https://github.com/ruuda/musium)                    | album-based music player                             | [Rud van Asseldonk](https://github.com/ruuda) ([website](https://ruudvanasseldonk.com/)) | Apache 2.0        | Rust                  |
| [nnnoiseless](https://github.com/jneem/nnnoiseless)          | clone of RNNoise from C++ for noise suppression      | [jneem](https://github.com/jneem)                                                        | BSD-3-Clause      | Rust                  |
| [orbtk](https://github.com/redox-os/orbtk)                   | GUI library for Rust                                 | [redox-os](https://github.com/redox-os)                                                  |                   | Rust                  |
| [pitch_calc](https://github.com/RustAudio/pitch_calc)        | Pitch Conversion Library                             | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |
| [rainout](https://github.com/MeadowlarkDAW/rainout)          | Cross-Platform Audio and MIDI I/O Library            | [MeadowlarkDAW](https://github.com/MeadowlarkDAW)                                        | Apache 2.0 or MIT | Rust                  |
| [Rodio](https://github.com/RustAudio/rodio)                  | Rust Audio playback library                          | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |
| [rubato](https://github.com/HEnquist/rubato)                 | Asynchronoous resampling                             | [Henrik Enquist](https://github.com/HEnquist) ([website](https://henquist.github.io/))   |                   | Rust                  |
| [rust_dct](https://github.com/ejmahler/rust_dct)             | cosine transform computation                         | [Elliott Mahler](https://github.com/ejmahler)                                            | Apache 2.0 or MIT | Rust                  |
| [rust-jack](https://github.com/RustAudio/rust-jack)          | Audio bindings for JACK                              | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | MIT               | Rust                  |
| [RustFFT](https://github.com/ejmahler/RustFFT)               | FFT Library                                          | [Elliott Mahler](https://github.com/ejmahler)                                            | Apache 2.0 or MIT | Rust                  |
| [slint](https://github.com/slint-ui/slint)                   | GUI library for Rust, C++, and JavaScript            | [SlintUI](https://github.com/slint-ui) ([website](https://slint-ui.com/))                | Apache 2.0        | Rust, C++, Typescript |
| [tauri](https://github.com/tauri-apps/tauri)                 | GUI library for Rust                                 | [tauri](https://github.com/tauri-apps) ([website](https://tauri.app/))                   | Apache 2.0 or MIT | Rust                  |
| [Tune](https://github.com/Woyten/tune/)                      | Xenharmonic Synth and Tuning                         | [Woyten](https://github.com/Woyten)                                                      | MIT License       | Rust                  |
| [whisper-rs](https://github.com/tazz4843/whisper-rs)         | Rust bindings for Whisper C++                        | [tazz4843](https://github.com/tazz4843)                                                  | Unilicense        | Rust                  |
| [wmidi](https://github.com/RustAudio/wmidi)                  | Rust encoding and decoding library                   | [Rust Audio](https://github.com/RustAudio) ([website](https://rust.audio/))              | Apache 2.0 or MIT | Rust                  |

## SuperCollider
| Name                                                                                        | Library Type                                  | Developer                                             | License     | Languages                         |
| :------------------------------------------------------------------------------------------ | :-------------------------------------------- | :-----------------------------------------------------| :---------- | :-------------------------------- |
| [apex-sc-dafx](https://github.com/musikinformatik/apex-sc-dafx)                             | vocal track modeling                          | [musikinformatik](https://github.com/musikinformatik) | GPL-2.0     | SuperCollider, C                  |
| [Generic Additive Synthesis](https://github.com/musikinformatik/Generic-Additive-Synthesis) | a guide to additive synthesis                 | [musikinformatik](https://github.com/musikinformatik) | None listed | None, examples with supercollider |
| [Steno](https://github.com/musikinformatik/Steno)                                           | a supercollider language for stringing synths | [musikinformatik](https://github.com/musikinformatik) | GPL-2.0     | SuperCollider                     |
| [SuperDirt](https://github.com/musikinformatik/SuperDirt)                                   | Implementation of the Dirt sampler            | [musikinformatik](https://github.com/musikinformatik) | GPL-2.0     | SuperCollider                     |
| [that](https://github.com/musikinformatik/that)                                             | realtime audio analysis                       | [musikinformatik](https://github.com/musikinformatik) | GPL-2.0     | SuperCollider                     |

## Swift
| Name               | Library Type              | Developer                                                                     | License     | Languages                         |
| :----------------- | :------------------------ | :---------------------------------------------------------------------------- | :---------- | :-------------------------------- |
| AudioKit           | Language/DSL              | [AudioKit](https://github.com/AudioKit) ([website](https://www.audiokit.io/)) | MIT         | Swift                             |
| AudioKit Flow      | Generic Node Graph Editor | [AudioKit](https://github.com/AudioKit) ([website](https://www.audiokit.io/)) | MIT         | Swift, Objective C, Objective C++ |
| AudioKit Synth One | Synthesizer App           | [AudioKit](https://github.com/AudioKit) ([website](https://www.audiokit.io/)) | MIT         | Swift, Objective C, Objective C++ |

## Additional Resources
| Name                                                                                                                     | Type                | Description                                    |
| :----------------------------------------------------------------------------------------------------------------------- | :------------------ | :--------------------------------------------- |
| [Awesome Open Source Synths](https://github.com/jonmoshier/awesome-open-source-synths)                                   | GitHub list         |                                                |
| [Awesome Synthesis](https://github.com/MikeMorenoDSP/awesome-synthesis)                                                  | GitHub list         |                                                |
| [Free DAW Software](https://bedroomproducersblog.com/2015/11/11/free-daw-software/)                                      | BPB Article         |                                                |
| [Free Synthesizer VST Plugins](https://bedroomproducersblog.com/2019/10/31/free-synthesizer-vst-plugins/)                | BPB Article         |                                                |
| [Free VST Plugins](https://bedroomproducersblog.com/free-vst-plugins/https://bedroomproducersblog.com/free-vst-plugins/) | BPB Article         |                                                |
| [Go Audio](https://github.com/go-audio)                                                                                  | GitHub Organization |                                                |
| [Microtonal-rust](https://github.com/Woyten/microtonal-rust)                                                             | Rust                | Rust Libraries Compilation                     |
| [musikinformatik](https://github.com/musikinformatik)                                                                    | Algorithm library   | Libraries for SuperCollider                    |
| [Rust.audio](https://rust.audio/)                                                                                        | Website             | Collection of Rust Audio Development Resources |
