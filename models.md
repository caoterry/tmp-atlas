# Tone Master Pro model list (firmware 1.8.58)

Every block you can pick on a Tone Master Pro running firmware 1.8.58, with its controls, grouped the way the unit groups them. The second column is the model's internal id as the unit reports it; it usually hints at the original gear. TMP display names avoid third-party trademarks.

## modulation (28)

| TMP name | FenderId | controls |
|---|---|---|
| Analog Chorus | `ACD_ChorusCE2` | Rate, Depth, Tap Div |
| Stereo Analog Chorus | `ACD_ChorusCE3` | Rate, Depth, Tap Div, Stereo |
| Analog Bass Chorus | `ACD_ChorusCE2B` | Rate, Depth, Tap Div, Level |
| Chorus | `ACD_Chorus_CE5Mono` | Rate, Depth, Mix, Tap Div, Low Cut, High Cut |
| Stereo Chorus | `ACD_Chorus_CE5Stereo` | Rate, Depth, Mix, Tap Div, Low Cut, High Cut, Width |
| 3D Chorus | `ACD_DimensionChorus` | Mode |
| JC Chorus | `ACD_JC120ChorusEffect` | Output |
| JC Vibrato | `ACD_JC120VibratoEffect` | Rate, Tap Div, Depth, Output |
| Triple-Double Chorus | `ACD_TriStereoChorus` | Preset, Manual, Rate, L Depth, C Depth, R Depth, Feedback, Sparkle, Stereo |
| Analog Vibrato | `ACD_VibratoVB2` | Rate, Depth, Tap Div, Rise Time |
| Flanger | `ACD_Flanger2p0Mono` | Rate, Depth, Res, Tap Div, Manual |
| Stereo Flanger | `ACD_Flanger2p0Stereo` | Rate, Depth, Res, Tap Div, Manual, L/R Phase |
| Electric Flanger | `ACD_ElectricMistress` | Rate, Depth, Color, Tap Div, Mode |
| '70s Flanger | `ACD_EvhFlanger` | Speed, Width, Regen, Tap Div, Manual |
| Orbit Stereo Panner | `ACD_StereoPanner` | Rate, Depth, Tap Div, Type |
| Phaser | `ACD_PhaserPH3` | Rate, Depth, Res, Tap Div, Mode, Stages |
| Phaser 90 | `ACD_PhaserP90` | Speed, Tap Div |
| Little Rock Phaser | `ACD_SmallStone` | Color, Rate, Tap Div |
| Tremolo | `ACD_TremoloSine` | Rate, Intensity, Duty Cycle, Tap Div, Shape, LFO Clip |
| Harmonic Tremolo | `ACD_TremoloHarmonic` | Speed, Intensity, Shape, Tap Div, Mode |
| Stereo Harmonic Tremolo | `ACD_PanoVerbTremolo` | Speed, Intensity, Shape, Tap Div |
| Optical Tremolo | `ACD_TMDR65Tremolo` | Speed, Intensity |
| Tube Bias Tremolo | `ACD_TremoloBias` | Speed, Tap Div, Intensity, Level |
| Step Tremolo | `ACD_StepTremolo` | Mix, Step Time, Tap Div, Spread, Glitch, Num Steps, Depth, Randomize, Step Smooth, Restart Seq, Gain 1, Gain 2, Gain 3, Gain 4, Gain 5, Gain 6, Gain 7, Gain 8 |
| Uni-Verse Vibe | `ACD_UniVibe` | Speed, Intensity, Volume, Tap Div, Mode, Mode |
| Rotary Speaker 122 | `ACD_PinwheelLeslie122` | Drive, Tone, Level, Fast, Slow, Speed, Ramp, Sense, Dynamics |
| Rotary Speaker 147 | `ACD_PinwheelLeslie147` | Drive, Tone, Level, Fast, Slow, Speed, Ramp, Sense, Dynamics |
| Vibratone | `ACD_TMPinwheelVibratone` | Drive, Tone, Level, Fast, Slow, Speed, Ramp, Sensitivity, Dynamics |

## stompbox (38)

| TMP name | FenderId | controls |
|---|---|---|
| Boost | `ACD_Boost` | Level |
| Integrator Boost | `ACD_TCIntegratedPre` | Treble, Bass, Level |
| Grunt Boost | `ACD_TCIntegratedPreStatic` | Level |
| Ranger Boost | `ACD_Rangemaster` | Level |
| SDD-Boost | `ACD_RackPreamp` | Input, Output, Level |
| XO Boost | `ACD_EPBooster` | Boost, Bright, Gain |
| Rockbox 100 | `ACD_Rockman` | Mode, Volume, Gain, Effects |
| Blues Maker | `ACD_BluesBreaker` | Gain, Tone, Volume, Version |
| Royal Tone | `ACD_KingOfTone` | Gain, Tone, Presence, Volume, Mode |
| Enchanter | `ACD_TimmyV3` | Gain, Bass, Treble, Volume, Boost |
| Greenbox 8 | `ACD_TubeScreamer` | Drive, Tone, Level, Blend |
| Greenbox 10 | `ACD_Greenbox10` | Drive, Tone, Level, Bass, Blend |
| Lightyear | `ACD_Lightspeed` | Drive, Loudness, Freq |
| Pinions | `ACD_Plumes` | Gain, Mode, Level, Tone |
| Runes | `ACD_Blumes` | Gain, Mode, Level, Tone |
| Sapphire Drive | `ACD_BluesDriver` | Gain, Level, Tone |
| Mythic Drive | `ACD_MythicDrive` | Gain, Treble, Output |
| Mythic Drive II | `ACD_KlonCentaur` | Gain, Treble, Output |
| Nashville Overdrive | `ACD_NobelsOdr1` | Drive, Level, Spectrum, Bass Cut |
| Tube OD | `ACD_TubeDriver` | Drive, Level, High, Low, Bias, Tube |
| Super Drive | `ACD_SD1` | Drive, Level, Tone |
| Orangebox | `ACD_DS1` | Distortion, Tone, Level |
| Hard-Clip Distortion | `ACD_DistortionPlus` | Distortion, Output |
| Maximus Drive | `ACD_Palladium` | Gain, Resonance, Level, Bass, Treble, Presence, Mid LVL, Mid Freq, Boost LVL, Boost |
| Pugilist Distortion | `ACD_Pugilist` | Gain A, Tone A, Level, Gain B, Tone B, Blend, Mode, Bass Boost |
| Comic Sans Drive | `ACD_ObsessiveDrive` | Drive, Filter, Level, Tone |
| Namaste Drive | `ACD_ZenDrive` | Gain, Volume, Tone, Voice |
| Rocket Man | `ACD_JRockettDude` | Drive, Level, Treble, Deep |
| Rodent | `ACD_Rat` | Distortion, Filter, Volume |
| Big Apple Fuzz | `ACD_BigFuzz` | Sustain, Level, Tone, Blend, Mids |
| Big Green Fuzz | `ACD_GreenRussianBmp` | Sustain, Level, Tone, Blend, Mids |
| Big Horn Fuzz | `ACD_RamsHeadBmp` | Sustain, Level, Tone, Blend, Mids |
| Round Fuzz - Germanium | `ACD_GeFuzzFace` | Fuzz, Volume |
| Round Fuzz - Silicon | `ACD_RoundFuzz` | Fuzz, Volume |
| Vari Fuzz | `ACD_VariFuzz` | Gain, Level, Filter |
| Octave Fuzz | `ACD_Octavia` | Boost, Volume, Octave |
| Octobot | `ACD_Octobot` | Direct, Down, Sizzle |
| Bass Overdrive | `ACD_ModernBassOverdrive` | Drive, Level, Blend, Bass, Treble, Presence |

## delay (32)

| TMP name | FenderId | controls |
|---|---|---|
| Space Delay | `ACD_SpaceEcho` | Time, Tap Div, Feedback, Mix, Rec Level, Dly Mode, Bass Level, Treb Level, Tape Noise, W & F |
| Stereo Space Delay | `ACD_SpaceEchoStereo` | Time, Tap Div, Mix, Head 1 Pan, Head 2 Pan, Head 3 Pan, Feedback, Rec Level, Dly Mode, Bass Level, Treb Level, Tape Noise, W & F |
| Tape Echo | `ACD_EchoplexEP3` | Time, Tap Div, Feedback, Mix, Rec Level, Tape Bias, Tape Noise, W & F |
| Stereo Tape Echo | `ACD_EchoplexEP3Stereo` | Time L, Tap Div L, Time R, Tap Div R, Feedback, Mix, Rec Level, Tape Bias, Tape Noise, W & F |
| Analog Delay | `ACD_DM2` | Time, Feedback, Mix, Tap Div |
| Echotank | `ACD_EchoMachine` | Time, Feedback, Mix, Tap Div |
| Memory Delay | `ACD_MemoryMan` | Time, Tap Div, Feedback, Mix, Depth, Gain, Grit, Mode |
| Stereo Memory Delay | `ACD_MemoryManStereo` | Time L, Time R, Tap Div L, Tap Div R, Feedback, Mix, Depth, Gain, Grit, Mode |
| Digital Delay | `ACD_BoilerPlateMono` | Time, Tap Div, Feedback, Mix, Tone |
| Stereo Digital Delay | `ACD_BoilerPlateStereo` | Time Left, Time Right, Feedback, Tap Div Left, Tap Div Right, Mix, Tone |
| Digital Hold Delay | `ACD_HoldDelay` | Time, Feedback, Mix, Tap Div, Hold, Lo-Fi, Glide |
| Stereo Digital Hold Delay | `ACD_HoldDelayStereo` | Time Left, Time Right, Feedback, Tap Division L, Tap Division R, Mix, Hold, Lo-Fi, Glide |
| Studio Delay | `ACD_ModDelay` | Time, Tap Div, Feedback, Mix, Low Cut, High Cut, Mod Rate, Mod Depth, Mod Mode, Pan Rate, Pan Depth, Pan Mode |
| Dynamic Delay | `ACD_DynamicDelay` | Time, Feedback, Mix, Tap Div, Low Cut, High Cut, Threshold, Atten, Release, Mod Rate, Mod Depth, Mod Mode |
| Aurora Delay | `ACD_HaloDelay` | Time, Feedback, Mix, Tap Div, Mode, Tone, Rate, Depth, Saturate, Low Cut |
| Stereo Aurora Delay | `ACD_HaloDelayStereo` | Time, Feedback, Mix, Tap Div, Mode, Tone, Rate, Depth, Saturate, Low Cut |
| Echelon Delay | `ACD_RackDelay` | Time, Tap Div, Feedback, Timescale, Diffusion, Mix, FB Inv, DLY Inv, Multiply, Mod Type, Mod Rate, Mod Depth, Hi-Cut, Hold |
| Stereo Echelon Delay | `ACD_RackDelayStereo` | Time Left, Time Right, Feedback, Tap Division L, Tap Division R, Mix, Mod Type, Mod Rate, Mod Depth, Stereo Mode, Timescale, Diffusion, Multiply, FB Inv, DLY Inv, Hi-Cut, Hold |
| Prime Delay | `ACD_MultiplyDelayMono` | Time, Tap Div, Feedback, Mix, Multiply, Lo-Fi, Mod Type, Mod Rate, Mod Depth, Hold |
| Stereo Prime Delay | `ACD_MultiplyDelay` | Time A, Time B, Feedback, Tap Div A, Tap Div B, Mix, Pan A, Pan B, Stereo Mode, Mod Type, Mod Rate, Mod Depth, Multiply, Lo-Fi, Hold |
| Auto-Swell Delay | `ACD_AutoSwellDelay` | Time, Feedback, Mix, Tap Div, Swell Time, Modulation, Tone, Sensitivity, Taper, Dry |
| Echo Filter | `ACD_TMDelayFilter` | Time, Tap Div, Feedback, Mix, F. Speed, F. Depth, Q, F. Mix |
| Stereo Echo Filter | `ACD_TMDelayFilterStereo` | Time, Tap Div, Offset, Spread, Feedback, Mix, F. Speed, F. Depth, Q, F. Mix |
| Ping Pong Delay | `ACD_TMPingPong` | Time, Tap Div, Feedback, Mix, Offset, Spread, High Cut |
| Reverse Delay | `ACD_TMReverse` | Time, Tap Div, Feedback, Mix, High Cut, Low Cut, Fwd Level |
| Polyhedron Pitch Delay | `ACD_Polyhedron` | Time 1, Tap Div 1, Pitch 1, Time 2, Tap Div 2, Pitch 2, Mix, Feedback, Attack, Spread, Crystallize, Lo-Fi |
| Step Filter Delay | `ACD_StepFilterDelay` | Time, Step Time, Feedback, Filter Type, Depth, Resonance, Delay Tap Div, Step Tap Div, Mix, Num Steps, Step Smooth, Spread, Pattern |
| Prismatic Delay | `ACD_SpectralDelay` | Time, Tap Div, Feedback, Density, Pattern, Attack, Spread, Pitch, Lo-Fi, Mix |
| Glooper | `ACD_Glooper` | Time, Layers, Repeats, Mix, Mode, Pitch, Spread, Reverse, Freeze, Overdub, Undo, Tap Div |
| Arctic Sustainer | `ACD_Freeze` | Dry, Wet, Freeze |
| Antarctic Sustainer | `ACD_DeepFreeze` | Freeze, Dry, Wet, Attack, Decay, Pitch, Gliss, Mode |
| Stereo Doubler | `ACD_Doubler` | Effect, Dry, Variation, Layers |

## reverb (28)

| TMP name | FenderId | controls |
|---|---|---|
| '63 Spring Reverb | `ACD_TMSpring63` | Mixer, Dwell, Tone |
| '63 Spring Reverb Convolution | `ACD_TMSpring63Conv` | Mixer, Dwell, Tone |
| '65 Spring Reverb | `ACD_TMSpring65` | Reverb, Tone |
| '65 Spring Reverb Convolution | `ACD_TMSpring65Conv` | Reverb |
| Small Room Reverb | `ACD_TMSmallRoom` | Mix, Pre-Delay, Decay, Damping, Diffuse, Room Size, High EQ, Low EQ, Disperse |
| Large Room Reverb | `ACD_TMLargeRoom` | Mix, Pre-Delay, Decay, Damping, Diffuse, Room Size, High EQ, Low EQ, Disperse |
| Small Hall Reverb | `ACD_TMSmallHall` | Mix, Pre-Delay, Decay, Damping, Diffuse, Hall Size, High EQ, Low EQ, Mod, Disperse |
| Large Hall Reverb | `ACD_TMLargeHall` | Mix, Pre-Delay, Decay, Damping, Diffuse, Hall Size, High EQ, Low EQ, Mod, Disperse |
| Modulated Small Hall Reverb | `ACD_FenderSmallModulatedHall` | Level, Decay, Dwell, Diffuse, Rate, Depth, High Cut, Low Cut |
| Modulated Large Hall Reverb | `ACD_FenderLargeModulatedHall` | Level, Decay, Dwell, Diffuse, Rate, Depth, High Cut, Low Cut |
| Small Plate Reverb | `ACD_TMSmallPlate` | Mix, Decay, Diffuse, Hi Damp, Low Damp, Hi Tone, Low Tone, Balance |
| Large Plate Reverb | `ACD_TMLargePlate` | Mix, Decay, Diffuse, Hi Damp, Low Damp, Hi Tone, Low Tone, Balance |
| Cirrostratus Reverb | `ACD_CirrostratusLite` | Decay, Modulation, Mix, Damping, High Cut, Low Cut, Gate |
| Cirrostratus Synthverb | `ACD_Cirrostratus` | Decay, Synthesis, Mix, Waveform, Cutoff, Attack, Pitch, Modulation, Damping, Gate, High Cut, Low Cut |
| Cloud Reverb | `ACD_CloudReverb` | Mix, Tone, Decay, Diffuse, High Damp, Low Damp, Rate, Depth |
| Celestial Reverb | `ACD_TMShimmer` | Mix, Decay, Pitch 1, Pitch 2, Pitch Decay, High Cut, Blend |
| Nebula Reverb | `ACD_NebulaTamed` | Mix, Size, Diffuse, Pitch, Pitch Dcy, Mod, High Cut, Low Cut |
| Reverse Nebula Reverb | `ACD_NebulaReverse` | Mix, Size, Diffuse, Pitch, Pitch Dcy, Response, Mod Rate, Mod Depth, High Cut, Low Cut |
| Shimmer Reverb | `ACD_SlimmerShimmer` | Mix, Decay, Damping, Diffuse, Feedback, HPF |
| Spectral Reverb | `ACD_SpectralReverb` | Decay, Tone, Mix, Spectrum, Pitch |
| Atmosphere Convolution Room | `ACD_TMAmbienceConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Vast Convolution Chamber | `ACD_TMChamberConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Ascension Convolution Hall | `ACD_TMCathedralConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Ethereal Convolution Hall | `ACD_TMEtherealHallConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Imperium Convolution Hall | `ACD_TMHallOfDoomConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Retrograde Convolution Hall | `ACD_TMNewAgeHallConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Alkaline Convolution Plate | `ACD_TMWarmPlateConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |
| Kinetic Convolution Plate | `ACD_TMRichPlateConv` | Mix, Pre-Delay, Low Cut, Treble, Wide |

## dynamicRange (12)

| TMP name | FenderId | controls |
|---|---|---|
| Dynamic Compressor | `ACD_DynaComp` | Output, Sensitivity |
| Pedal Comp | `ACD_CS3` | Level, Tone, Attack, Comp |
| Seventy Sixer Compressor | `ACD_UA1176` | Input, Output, Attack, Release, Dry, Ratio, Meter, GR OFF, Gain Reduction |
| Simple Compressor | `ACD_CompressorSimple` | Type |
| Studio Compressor | `ACD_CompressorSimpleSoftKnee` | Gain, Threshold, Ratio, Attack, Release, Knee, Blend, Gain Reduction |
| Sustain | `ACD_Sustain` | Sensitivity, Output |
| Metal Gate | `ACD_ChromeGate` | Threshold, Attenuation |
| Noise Gate | `ACD_NoiseGate` | Threshold, Attenuation |
| Simple Gate | `ACD_NoiseGateMustang` | Type |
| Volume Pedal | `ACD_VolumePedal` | Volume |
| Auto-Swell Volume | `ACD_VolumeSwell` | Time, Sense, Taper |
| Slow Attack | `ACD_SlowAttack` | Attack |

## eq (11)

| TMP name | FenderId | controls |
|---|---|---|
| EQ-5 Graphic | `ACD_MustangFiveBandEq1` | 80, 240, 750, 2.2K, 6.6K, Gain |
| EQ-7 Graphic | `ACD_MustangSevenBandEq` | 100, 200, 400, 800, 1.6K, 3.2K, 6.4K, Gain |
| EQ-7B Bass Graphic | `ACD_TMBassGraphicEQ7` | 62, 125, 250, 500, 1K, 2K, 4K, Gain |
| EQ-7W Bass Graphic | `ACD_TMGraphicEQ7Wide` | 50, 120, 400, 500, 800, 4.5K, 10K, Gain |
| EQ-10 Graphic | `ACD_TenBandEQStereo` | 31, 62, 125, 250, 500, 1K, 2K, 4K, 8K, 16K, Gain |
| EQ-3 Parametric | `ACD_MustangPEQ` | Bass, Mid, Mid Freq, Mid Q, Treble, Gain |
| EQ-5 Parametric | `ACD_FiveBandParamEQ` | Type 1, Freq 1, Q 1, Gain 1, Order 1, Bypass 1, Type 2, Freq 2, Q 2, Gain 2, Order 2, Bypass 2, Type 3, Freq 3, Q 3, Gain 3, Order 3, Bypass 3, Type 4, Freq 4, Q 4, Gain 4, Order 4, Bypass 4, Type 5, Freq 5, Q 5, Gain 5, Order 5, Bypass 5, Level |
| Low/High Cut Filter | `ACD_HighLowPass` | LC Bypass, LC Freq, LC Order, HC Bypass, HC Freq, HC Order |
| High Cut Filter | `ACD_LowPass` | Freq, Q, Order |
| Low Cut Filter | `ACD_HighPass` | Freq, Q, Order |
| Notch Filter | `ACD_NotchFilter` | Freq, Gain, Q |

## filter (6)

| TMP name | FenderId | controls |
|---|---|---|
| Custom Wah | `ACD_CryBabyQ535` | Position, Range, Q, Inductor |
| Teardrop Wah | `ACD_CryBabyGCB95` | Position |
| Vocal Wah | `ACD_CryBabyV847` | Position |
| Filtron | `ACD_MicroTronIV` | Level, Peak, Gain, Mode, Direction, Range |
| Enigma Filter | `ACD_KorgA2AutoWah` | Sens, Freq, Res, Attack, Release |
| Step Filter | `ACD_StepFilter` | Mix, Step Time, Filter Type, Depth, Randomize, Spread, Resonance, Tap Div, Num Steps, Glitch, Step Smooth, Restart Seq, Cutoff 1, Cutoff 2, Cutoff 3, Cutoff 4, Cutoff 5, Cutoff 6, Cutoff 7, Cutoff 8 |

## pitch (11)

| TMP name | FenderId | controls |
|---|---|---|
| Micro Shifter | `ACD_MicroPitch` | Mix, Pitch L, Pitch R, Spread, Delay L, Delay R, Feedback |
| Chromatic Pitch Shifter | `ACD_ChromaticPitchShifter` | Mix, Pitch, Delay, Tap Div, Feedback, Tone |
| Polygon Octave Shifter | `ACD_POG` | Original, -2Oct, -Oct, +5th, +Oct, +2Oct, Attack, Hi-Cut |
| PolyVoice Pitch Shifter | `ACD_PolyChord` | Voice 1, Voice 2, Voice 3, Mix, Attack, Lo-Fi |
| Diatonic Pitch Shifter | `ACD_DiatonicPitchShifter` | Mix, Pitch, Key, Tone, Scale, Delay, Feedback, Tap Div |
| Feedback Generator | `ACD_Freqout` | Attack, Level, Type |
| Pedal Detune | `ACD_WhammyV5Detune` | Range, Position |
| Pedal Shifter | `ACD_WhammyV5Classic` | Pitch, Position |
| Virtual Capo | `ACD_PolyPitchShifter` | Mix, Resolution, Tracking, Pitch |
| Granular Arpeggiator | `ACD_GranularArp` | Mix, Time, Scale, Range, Direction, Steps, Layers, Speed, Glitch, Pitch, Time Divider, Reverse, Spread, Armed, Tap Div |
| Pitch Sequencer | `ACD_PitchSequencer` | Mix, Step Time, Pitch Glitch, Glide, Randomize, Spread, Speed Glitch, Tap Division, Num Steps, Freeze Mode, Freeze, Restart Seq, Step 1, Step 2, Step 3, Step 4, Step 5, Step 6, Step 7, Step 8 |

## synth (3)

| TMP name | FenderId | controls |
|---|---|---|
| Aethon | `ACD_GuitarSynthLite` | Preset, Attack, Cutoff, Resonance, Envelope Amount, Envelope Sensitivity, Wave Shape, Wave Pitch, Pitch Wheel, Freeze Mode, Freeze, Freeze Gliss, LFO Shape, LFO Target, Spread, LFO Depth, LFO Rate, LFO Tap Div, Mix, Volume |
| Cerberus | `ACD_GuitarSynth` | Preset, Attack, Cutoff, Resonance, Envelope Amount, Envelope Sensitivity, Wave 1 Shape, Wave 1 Lvl, Wave 1 Pitch, Wave 2 Shape, Wave 2 Lvl, Wave 2 Pitch, Wave 3 Shape, Wave 3 Lvl, Wave 3 Pitch, Freeze Mode, Freeze, Freeze Gliss, Filter LFO Shape, Filter LFO Depth, Filter LFO Rate,  Filter LFO Tap Div, Spread, Mix, Pitch LFO Shape, Pitch LFO Depth, Pitch LFO Rate,  Pitch LFO Tap Div, Detune, Pitch Wheel, Volume LFO Shape, Volume LFO Depth, Volume LFO Rate, Volume LFO Tap Div, Volume |
| Wavemorph | `ACD_WaveMorphSynth` | Preset, Attack, Cutoff, Resonance, Envelope Amount, Envelope Sensitivity, Wave Shape, Wave Morph, Wave Pitch, Envelope Target, Volume, Pitch Wheel, LFO Shape, LFO Target, Spread, LFO Depth, LFO Rate, LFO Tap Div, Freeze Mode, Freeze, Freeze Gliss, Mix |

## head (55)

| TMP name | FenderId | controls |
|---|---|---|
| '57 Champ | `ACD_TMChamp57` | Volume, Amp Level |
| '57 Deluxe | `ACD_TweedDeluxe` | Mic. Vol, Inst. Vol, Tone, Amp Level |
| '59 Bassman | `ACD_TM59Bassman` | Vol Normal, Vol Bright, Treble, Middle, Bass, Presence, Amp Level |
| '59 Bassman Custom | `ACD_TMCust59Bassman` | Vol Normal, Vol Bright, Treble, Middle, Bass, Presence, Amp Level |
| '62 Princeton | `ACD_Princeton6G2` | Volume, Tone, Speed, Intensity, Amp Level |
| '65 Princeton Reverb (Amp Only) | `ACD_PrincetonReverb65NoFx` | Volume, Treble, Bass, Amp Level |
| '65 Deluxe Reverb (Amp Only) | `ACD_DeluxeReverb65NoFx` | Volume, Treble, Bass, Amp Level |
| '65 Deluxe Reverb Blonde NBC (Amp Only) | `ACD_DeluxeReverb65BlondeVibratoNoFx` | Volume, Treble, Bass, Amp Level |
| '65 Super Reverb (Amp Only) | `ACD_TMSuperReverbNoFx` | Bright, Volume, Treble, Middle, Bass, Amp Level |
| '65 Twin Reverb (Amp Only) | `ACD_TwinReverb65NoFx` | Bright, Volume, Treble, Middle, Bass, Amp Level |
| '65 Twin Reverb Blonde (Amp Only) | `ACD_TwinReverb65BlondeNoFx` | Bright, Volume, Treble, Middle, Bass, Amp Level |
| '68 Custom Princeton Reverb (Amp Only) | `ACD_PrincetonReverb68NoFx` | Volume, Treble, Bass, Amp Level |
| '68 Custom Deluxe Reverb (Amp Only) | `ACD_DeluxeReverb68CustomNoFx` | Volume, Treble, Bass, Amp Level |
| Bassbreaker Low | `ACD_Bassbreaker15` | Bright, Gain, Bass, Middle, Treble, Master, Amp Level |
| Bassbreaker Med | `ACD_Bassbreaker15Med` | Bright, Gain, Bass, Middle, Treble, Master, Amp Level |
| Bassbreaker High | `ACD_Bassbreaker15High` | Bright, Gain, Bass, Middle, Treble, Master, Amp Level |
| Blues Junior | `ACD_BluesJrIV` | Fat, Volume, Treble, Middle, Bass, Master, Amp Level |
| Blues Junior LTD | `ACD_BluesJrIVLTD` | Fat, Volume, Treble, Middle, Bass, Master, Amp Level |
| Vibro-King | `ACD_VibroKing` | Fat, Volume, Treble, Bass, Mid, Amp Level |
| UK30 Brilliant | `ACD_AC30Brilliant` | Volume, Treble, Bass, Cut, Amp Level |
| UK30 Normal | `ACD_AC30Normal` | Volume, Cut, Amp Level |
| Brit Breaker | `ACD_JTM45TremCombo` | Volume I, Volume II, Treble, Middle, Bass, Presence, Speed, Intensity, Amp Level |
| British 45 | `ACD_JTM45Head` | Volume I, Volume II, Treble, Middle, Bass, Presence, Amp Level |
| British Plexi | `ACD_MarshallPlexi` | Volume I, Volume II, Treble, Middle, Bass, Presence, Amp Level |
| British 800 | `ACD_JCM800TMS` | Gain, Master, Treble, Middle, Bass, Presence, Amp Level |
| British Jubilee Clean | `ACD_Jubilee` | Gain, Master, Treble, Middle, Bass, Presence, Amp Level |
| British Jubilee Rhythm | `ACD_JubileeClip` | Gain, Master, Treble, Middle, Bass, Presence, Amp Level |
| British Jubilee Lead | `ACD_JubileeLead` | Gain, Master, Treble, Middle, Bass, Presence, Amp Level |
| Hiway 105 | `ACD_HiwattDR103CanMod` | Normal Vol, Bright Vol, Bass, Treble, Middle, Presence, Master Vol, Amp Level |
| Forge 100 | `ACD_BE100` | Gain, Master, Treble, Middle, Bass, Presence, HBE, FAT, C45, SAT, VCE, Amp Level |
| EVH 5150 III 6L6 Green | `ACD_HypersonicAmp6L6Green` | Gain, Low, Mid, High, Volume, Presence, Resonance, Amp Level |
| EVH 5150 III 6L6 Blue | `ACD_HypersonicAmp6L6Blue` | Gain, Low, Mid, High, Volume, Presence, Resonance, Amp Level |
| EVH 5150 III 6L6 Red | `ACD_HypersonicAmp6L6Red` | Gain, Low, Mid, High, Volume, Presence, Resonance, Amp Level |
| EVH 5150 IIIS 6L6 Green | `ACD_Evh100SGreen` | Gain, Volume, Low, Mid, High, Presence, Resonance, Amp Level |
| EVH 5150 IIIS 6L6 Blue | `ACD_Evh100SBlue` | Gain, Volume, Low, Mid, High, Presence, Resonance, Amp Level |
| EVH 5150 IIIS 6L6 Red | `ACD_Evh100SRed` | Gain, Volume, Low, Mid, High, Presence, Resonance, Amp Level |
| Solo 100 Overdrive | `ACD_SLO100` | Gain, Master, Bass, Middle, Treble, Presence, Depth, Amp Level |
| Tangerine RV53 | `ACD_OrangeRockerverb50MKIII` | Gain, Volume, Treble, Middle, Bass, Amp Level |
| Marksman Ch1 | `ACD_MarkIICClassA` | Volume, Treble, Middle, Bass, Presence, Master, GEQ, 80, 240, 750, 2.2K, 6.6K, Bright, Treb Shift, Bass Shift, Deep, Amp Level |
| Marksman Ch2 | `ACD_MarkIICClassAB` | Gain, Treble, Middle, Bass, Presence, Master, GEQ, 80, 240, 750, 2.2K, 6.6K, Bright, Treb Shift, Bass Shift, Deep, Ld Bright, Amp Level |
| Double Wreck | `ACD_DualRectifier` | Gain, Master, Treble, Middle, Bass, Presence, Amp Level |
| Petrol | `ACD_DiezelVh4Ch3` | Gain, Volume, Treble, Middle, Bass, Presence, Deep, Amp Level |
| Uber | `ACD_Uberschall` | Gain, Volume, Treble, Middle, Bass, Presence, Amp Level |
| JC Clean | `ACD_JC120` | Bright, Volume, Treble, Middle, Bass, Amp Level |
| Acoustasonic | `ACD_Acoustasonic` | Gain, Treble, Middle, Bass, String Dynamics, Dynamics Frequency, Amp Level |
| Studio Preamp | `ACD_StudioPreamp` | Gain, Treble, Middle, Bass, Amp Level |
| Tube Preamp | `ACD_StudioTubePreamp` | Gain, Treble, Middle, Mid Freq, Bass, Amp Level |
| Bassman TV | `ACD_TMBassmanTV` | Bright, Gain, Bass, Middle, Treble, Volume, Deep, Amp Level |
| Rumble 800 | `ACD_TMRumbleV3` | Gain, Bright, Contour, Vintage, Drive, Overdrive, Level, Bass, Low Mid, High Mid, Treble, Master, Amp Level |
| Super Bassman Vintage | `ACD_SuperBassmanVintage` | Volume, Bass, Mid, Treble, Master, Deep, Bright, Amp Level |
| Super Bassman Overdrive | `ACD_SuperBassman` | Gain, Blend, Bass, Mid Freq, Mid Level, Treble, Master, Deep, Bright, Amp Level |
| SWR Redhead | `ACD_Redhead` | Gain, Enhancer, Bass, Mid-Lvl, Mid-Freq, Treble, Compressor, Master, Turbo, Transparency, Amp Level |
| Rampage Blueline | `ACD_SVTBlueLine` | Volume, Treble, Midrange, Bass, Ultra Lo, Mid Freq, Ultra Hi, Amp Level |
| '66 Flip-Top | `ACD_Ampeg66B15` | Volume, Bass, Mid, Treble, Amp Level |
| Rock-Bottom 400 | `ACD_GK800RB` | Volume, Treble, Hi-Mid, Lo-Mid, Bass, Master, Lo Cut, Mid Contour, Hi Boost, Boost, Boost, Amp Level |

## combos (36)

| TMP name | FenderId | controls |
|---|---|---|
| '57 Champ | `ACD_TMChamp57CabIR` | Volume, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '57 Deluxe | `ACD_TweedDeluxeCabIR` | Mic. Vol, Inst. Vol, Tone, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '59 Bassman | `ACD_TM59BassmanCabIR` | Vol Normal, Vol Bright, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '59 Bassman Custom | `ACD_TMCust59BassmanCabIR` | Vol Normal, Vol Bright, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '62 Princeton | `ACD_Princeton6G2CabIR` | Volume, Tone, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Princeton Reverb | `ACD_PrincetonReverb65CabIRConvRvb` | Volume, Treble, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Princeton Reverb (Amp Only) | `ACD_PrincetonReverb65NoFxCabIR` | Volume, Treble, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Deluxe Reverb | `ACD_DeluxeReverb65VibratoCabIRConvRvb` | Volume, Treble, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Deluxe Reverb (Amp Only) | `ACD_DeluxeReverb65NoFxCabIR` | Volume, Treble, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Deluxe Reverb Blonde NBC | `ACD_DeluxeReverb65BlondeVibratoCabIRConvRvb` | Volume, Treble, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Deluxe Reverb Blonde NBC (Amp Only) | `ACD_DeluxeReverb65BlondeVibratoNoFxCabIR` | Volume, Treble, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Super Reverb | `ACD_TMSuperReverbVibratoCabIRConRvb` | Bright, Volume, Treble, Middle, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Super Reverb (Amp Only) | `ACD_TMSuperReverbNoFxCabIR` | Bright, Volume, Treble, Middle, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Twin Reverb | `ACD_TwinReverb65VibratoCabIRConvRvb` | Bright, Volume, Treble, Middle, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Twin Reverb (Amp Only) | `ACD_TwinReverb65NoFxCabIR` | Bright, Volume, Treble, Middle, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Twin Reverb Blonde | `ACD_TwinReverb65BlondeVibratoCabIRConvRvb` | Bright, Volume, Treble, Middle, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Twin Reverb Blonde (Amp Only) | `ACD_TwinReverb65BlondeNoFxCabIR` | Bright, Volume, Treble, Middle, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Twin Custom 15 | `ACD_TwinReverbCustom15VibratoCabIRConvRvb` | Bright, Volume, Treble, Middle, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '65 Twin Custom 15 (Amp Only) | `ACD_TwinReverbCustom15NoFxCabIR` | Bright, Volume, Treble, Middle, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '68 Custom Princeton Reverb | `ACD_PrincetonReverb68CabIRConvRvb` | Volume, Treble, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '68 Custom Princeton Reverb (Amp Only) | `ACD_PrincetonReverb68NoFxCabIR` | Volume, Treble, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '68 Custom Deluxe Reverb | `ACD_DeluxeReverb68CustomCabIRConvRvb` | Volume, Treble, Bass, Reverb, Speed, Intensity, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '68 Custom Deluxe Reverb (Amp Only) | `ACD_DeluxeReverb68CustomNoFxCabIR` | Volume, Treble, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Bassbreaker Low | `ACD_Bassbreaker15CabIR` | Bright, Gain, Bass, Middle, Treble, Master, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Bassbreaker Med | `ACD_Bassbreaker15MedCabIR` | Bright, Gain, Bass, Middle, Treble, Master, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Blues Junior | `ACD_BluesJrIVCabIR` | Fat, Volume, Treble, Middle, Bass, Master, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Blues Junior LTD | `ACD_BluesJrIVLTDCabIR` | Fat, Volume, Treble, Middle, Bass, Master, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Vibro-King | `ACD_VibroKingCabIR` | Fat, Volume, Treble, Bass, Mid, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| EVH 5150 III 6L6 Green | `ACD_HypersonicAmp6L6GreenCabIR` | Gain, Low, Mid, High, Volume, Presence, Resonance, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| EVH 5150 III 6L6 Blue | `ACD_HypersonicAmp6L6BlueCabIR` | Gain, Low, Mid, High, Volume, Presence, Resonance, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| EVH 5150 III 6L6 Red | `ACD_HypersonicAmp6L6RedCabIR` | Gain, Low, Mid, High, Volume, Presence, Resonance, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Brit Breaker | `ACD_JTM45TremComboCabIR` | Volume I, Volume II, Treble, Middle, Bass, Presence, Speed, Intensity, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| UK30 Brilliant | `ACD_AC30BrilliantCabIR` | Volume, Treble, Bass, Cut, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| UK30 Normal | `ACD_AC30NormalCabIR` | Volume, Cut, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Marksman Ch1 | `ACD_MarkIICClassACabIR` | Volume, Treble, Middle, Bass, Presence, Master, GEQ, 80, 240, 750, 2.2K, 6.6K, Bright, Treb Shift, Bass Shift, Deep, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| JC Clean | `ACD_JC120CabIR` | Bright, Volume, Treble, Middle, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |

## halfstacks (18)

| TMP name | FenderId | controls |
|---|---|---|
| Bassbreaker High | `ACD_Bassbreaker15HighCabIR` | Bright, Gain, Bass, Middle, Treble, Master, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| British 45 | `ACD_JTM45HeadCabIR` | Volume I, Volume II, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| British Plexi | `ACD_MarshallPlexiCabIR` | Volume I, Volume II, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| British 800 | `ACD_JCM800TMSCabIR` | Gain, Master, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| British Jubilee Clean | `ACD_JubileeCabIR` | Gain, Master, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| British Jubilee Rhythm | `ACD_JubileeClipCabIR` | Gain, Master, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| British Jubilee Lead | `ACD_JubileeLeadCabIR` | Gain, Master, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Hiway 105 | `ACD_HiwattDR103CanModCabIR` | Normal Vol, Bright Vol, Bass, Treble, Middle, Presence, Master Vol, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Forge 100 | `ACD_BE100CabIR` | Gain, Master, Treble, Middle, Bass, Presence, HBE, FAT, C45, SAT, VCE, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| EVH 5150 IIIS 6L6 Green | `ACD_Evh100SGreenCabIR` | Gain, Volume, Low, Mid, High, Presence, Resonance, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| EVH 5150 IIIS 6L6 Blue | `ACD_Evh100SBlueCabIR` | Gain, Volume, Low, Mid, High, Presence, Resonance, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| EVH 5150 IIIS 6L6 Red | `ACD_Evh100SRedCabIR` | Gain, Volume, Low, Mid, High, Presence, Resonance, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Solo 100 Overdrive | `ACD_SLO100CabIR` | Gain, Master, Bass, Middle, Treble, Presence, Depth, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Tangerine RV53 | `ACD_OrangeRockerverb50MKIIICabIR` | Gain, Volume, Treble, Middle, Bass, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Marksman Ch2 | `ACD_MarkIICClassABCabIR` | Gain, Treble, Middle, Bass, Presence, Master, GEQ, 80, 240, 750, 2.2K, 6.6K, Bright, Treb Shift, Bass Shift, Deep, Ld Bright, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Double Wreck | `ACD_DualRectifierCabIR` | Gain, Master, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Petrol | `ACD_DiezelVh4Ch3CabIR` | Gain, Volume, Treble, Middle, Bass, Presence, Deep, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Uber | `ACD_UberschallCabIR` | Gain, Volume, Treble, Middle, Bass, Presence, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |

## cabinets (63)

| TMP name | FenderId | controls |
|---|---|---|
| 1x8 '57 Champ | `ACD_Fen57Champ` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x10 '62 Princeton C10R | `ACD_FenBrownPrincetonJenC10R` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x10 '65 Princeton C10R | `ACD_FenPrincetonRvb_jensen` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x10 '65 Princeton GB | `ACD_FenPrincGB` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x10 '68 Princeton | `ACD_Fen68PrinceG10R30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 '57 Deluxe | `ACD_Fen57CustomDeluxe_eminence` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 Deluxe Blue | `ACD_Fen57DlxBlue` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 '62 Princeton CS | `ACD_FenBrownPrincetonCS12` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 '65 Deluxe C12K | `ACD_FenDlxRvb_c12k` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 '65 Deluxe CB | `ACD_FenDlxRvbTMCream_g12neo` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 '65 Deluxe GB | `ACD_Fen65DlxGB` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 '68 Deluxe | `ACD_Fen68DlxG12V70` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 Deluxe D120 | `ACD_Fen65DlxJBLD120f` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 Bassbreaker | `ACD_Fen_Bassbreaker_Celestion_G12V_70` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 Blues Jr A-Type | `ACD_BlsJrIV_CelestionTypeA` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 Blues Jr LTD C12N | `ACD_BlsJrIV_Jensen_C12N` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 EVH 5150 G12H | `ACD_Hypersonic_112` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x12 Mega EV | `ACD_Mbg_MkIICPlus_EVM12L` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x15 Twin Custom | `ACD_FenTwinEmi15` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 '65 Twin C12K | `ACD_FenTwnRvb_Jensen_C12K` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 '65 Twin CB | `ACD_FenTwnRvbTMCream_g12neo` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 Twin D120 | `ACD_Fen65TwinJBLD120f` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 JC | `ACD_RolJazzChorus_JC120` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 British Alnico 100 | `ACD_Mar212Cent100` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 British Greenback | `ACD_British212Greenback` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 British Jubilee | `ACD_Msh_Jubilee_Slant_Celestion_G12Vintage` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 UK30 Alnico Blue | `ACD_VoxAC30_Celestion_G12_Alinco_Blue` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 UK30 Greenback | `ACD_VoxAC30_Celestion_Greenback` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x12 Vibro-King V30 | `ACD_FenVibroKing_2x12_v30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 3x10 Vibro-King | `ACD_FenVibKng_p10rf` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x10 '59 Bassman | `ACD_FenBassman_Jensen_Special` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x10 '59 Bassman Greenback | `ACD_FenBassmanGB` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x10 '65 Super Reverb | `ACD_FenSuperRvb_p10r` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 BassBreaker V30 | `ACD_FenBassBreaker412V30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British Alnico 100 | `ACD_Mar412Cent100` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British Blackback | `ACD_MarG12H30BB` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British Greenback | `ACD_Mar1960tvGB` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British G12H | `ACD_Evh412G12H30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British G65 | `ACD_Mar412G1265` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British V30 | `ACD_Mar1960aV30Alt` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British Jubilee V30 | `ACD_Mar1960aV30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 British T75 | `ACD_Marshall_JCM800_1960A` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 EVH 5150 IIIS | `ACD_Evh5150iii_4x12_Celestion_G12_EVH` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Forge Greenback | `ACD_Fried_BE4x12_Greenback_V30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Forge V30 | `ACD_Fried_BE4x12_V30_Greenback` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Hiway | `ACD_Hiwatt412Fane` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Mega Shadow | `ACD_Mbg412HBBSClosed` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Mega V30 | `ACD_Mbg_RectifierTrad_CelestionV30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Petrol V30 | `ACD_Diezel412FV` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Solo G12 | `ACD_Sol_4x12_Slant_G12H` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Tangerine V30 | `ACD_OrangePPC412` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Uber T75 | `ACD_Bogner_412STU_Celestion_G12H` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x12 Uber V30 | `ACD_Bogner_412STU_Celestion_G12_V30` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 2x10 SWR Redhead | `ACD_Redhead210` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x10 Rock-Bottom | `ACD_GKCX410` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 4x10 Bassman Pro Neo | `ACD_FenBassman410Neo` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 6x10 Bassman Pro Neo | `ACD_FenBassman610Neo` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 8x10 Bassman Pro Neo | `ACD_FenBassman810Neo` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 8x10 Rampage Bass | `ACD_Ampeg810E` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x15 Bassman Pro Neo | `ACD_FenBassman115Neo` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x15 Bassman TV | `ACD_BassmanTV115` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| 1x15 Rampage Bass | `ACD_FlipTop` | Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut |
| External Cabinet | `ACD_ExternalCab` | Speaker Impedance Curve, Low Cut, Low Freq, LF Res, LF Q, Cabinet Resonance, High Freq, HF Res, HF Q, High Cut, Level |

## bassAmps (8)

| TMP name | FenderId | controls |
|---|---|---|
| Bassman TV | `ACD_TMBassmanTVCabIR` | Bright, Gain, Bass, Middle, Treble, Volume, Deep, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Rumble 800 | `ACD_TMRumbleV3CabIR` | Gain, Bright, Contour, Vintage, Drive, Overdrive, Level, Bass, Low Mid, High Mid, Treble, Master, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Super Bassman Vintage | `ACD_SuperBassmanVintageCabIR` | Volume, Bass, Mid, Treble, Master, Deep, Bright, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Super Bassman Overdrive | `ACD_SuperBassmanCabIR` | Gain, Blend, Bass, Mid Freq, Mid Level, Treble, Master, Deep, Bright, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| SWR Redhead | `ACD_RedheadCabIR` | Gain, Enhancer, Bass, Mid-Lvl, Mid-Freq, Treble, Compressor, Master, Turbo, Transparency, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Rampage Blueline | `ACD_SVTBlueLineCabIR` | Volume, Treble, Midrange, Bass, Ultra Lo, Mid Freq, Ultra Hi, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| '66 Flip-Top | `ACD_Ampeg66B15CabIR` | Volume, Bass, Mid, Treble, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Amp Level, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |
| Rock-Bottom 400 | `ACD_GK800RBCabIR` | Volume, Treble, Hi-Mid, Lo-Mid, Bass, Master, Lo Cut, Mid Contour, Hi Boost, Boost, Boost, Amp Level, Cabinet, Mic, Mic Position, Mic Distance, Mic Axis, High Cut, Low Cut, Cabinet2, Mic 2, Mic 2 Position, Mic 2 Distance, Mic 2 Axis, High Cut 2, Low Cut 2, Enable Mic 2, Pan 1, Pan 2, Blend |

## fxLoops (3)

| TMP name | FenderId | controls |
|---|---|---|
| FX Loop 3 | `ACD_FxLoop3` | Spillover |
| FX Loop 4 | `ACD_FxLoop4` | Spillover |
| FX Loop 3+4 Stereo | `ACD_FxLoop3_4` | Spillover |

