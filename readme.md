# A collection of VCV Rack modules based on audio plugins by Chris Johnson from Airwindows

![Rackwindows Modules](res/images/rackwindows_panels.jpg)

Most of these modules are straight-up ports of [Airwindows](http://www.airwindows.com) plugins with the addition of a panel (designed to be potentially buildable in hardware) and the occasional tweak or enhancement to take advantage of the modular environment.

Airwindows plugins are known for exceptional sound quality, innovative approaches and minimalist interfaces. They often focus on and excel at one specific task, which is why I think they are a natural fit for Rack.

For more in-depth information about the inner workings of a particular Airwindows plugin please check Chris' [website](http://www.airwindows.com). There is a video on every plugin along with a description and I encourage everyone to explore his body of work. Chances are you stumble upon other gems here and there. He's got a [Patreon](https://www.patreon.com/airwindows) in case you appreciate and want to support what he does.

**NOTE:** Some modules act a bit differently depending on the selected sample rate and I'm looking for a fix. Keep in mind that some Airwindows plugins are actually sample rate dependent, therefore in some cases it might indeed be a feature, not a bug. There are definitely differences though between the plugin versions and the ported modules with regards to sample rate and I haven't found the explanation yet, let alone a solution. As far as I can tell, all modules behave correctly at 44.1 kHz.

## Licence

See [LICENSE.md](LICENSE.md) for all licenses

## Modules

- [Capacitor Mono/Stereo](#capacitor): Filters
- [Chorus](#chorus): Chorus with multi-tap option (Ensemble)
- [Console](#console): Stereo summing mixer
- [Distance](#distance): Designed to mimic through-air high frequency attenuation
- [Dual BSG](#dual-bsg): Dual gain shifter
- [Holt](#holt): Resonant lowpass filter focussed on low frequencies
- [Hombre](#hombre): Texas tone and texture
- [Interstage](#interstage): Subtle analogifier
- [MV](#mv): Dual-mono reverb
- [ResEQ](#reseq): Resonance equalizer
- [Tape](#tape): All-purpose tape mojo
- [Tremolo](#tremolo): Organic pulsating thing
- [Vibrato](#vibrato): FM Vibrator o_O

## Capacitor <a id="capacitor"></a>

Filters

![Rackwindows Capacitor](res/images/capacitor_panels.jpg)

High/Lowpass filters that come in both mono and stereo, with the stereo version featuring an additional dry/wet control.

[More information](http://www.airwindows.com/capacitor)

## Chorus <a id="chorus"></a>

Chorus with multi-tap option (Ensemble) 

![Rackwindows Chorus](res/images/chorus_panels.jpg)

This surprisingly versatile module is a combination of Airwindows Chorus and ChorusEnsemble. The switch lets you toggle between the two flavours.

[More information](http://www.airwindows.com/chorus-vst)

## Console <a id="console"></a>

![Rackwindows Console](res/images/console_panels.jpg)

Airwindows Console systems sum signals in a way where the resulting soundstage appears less flat, more spacious and more in line with what we are used to from analog mixers. There are a number of variations/flavours of the console concept and this module currently implements the most recent one, Console6, and PurestConsole, which can be selected in the context menu. 

Please check the link below for further information on how exactly this effect is achieved.

**NOTE**: Due to how the encoding/decoding works, spaciousness and definition will increase with each additional channel. There will be **no effect on a single channel** at all.

[More information](http://www.airwindows.com/console2)

## Distance <a id="distance"></a>

Designed to mimic through-air high frequency attenuation

![Rackwindows Distance](res/images/distance_panels.jpg)

Pushes things back. Also quite nice on reverb returns.

[More information](http://www.airwindows.com/distance-vst)

## Dual BSG <a id="dual-bsg"></a>

Dual gain shifter

![Rackwindows Dual BSG](res/images/dual_bsg_panels.jpg)

Scales a signal up or down by increments of exactly 6 dB. If no input is connected, the respective output will provide constant voltage selectable in 1V steps from -8V to +8V. The lower section can be linked to the upper one to automatically compensate for values set by the upper 'Shift' knob. If linked the lower 'Shift' knob can be used to offset the signal in 6db steps (input connected) or 1V steps (input not connected). 

[More information](http://www.airwindows.com/bitshiftgain)

## Holt <a id="holt"></a>

Resonant lowpass filter focussed on low frequencies

![Rackwindows Hombre](res/images/holt_panels.jpg)

Interestingly, Holt's algorithm is based on an Excel method for predicting sales figures based on trends. The result is a lowpass filter that's polite in the highs and increasingly mean towards the low-end. It also allows for seamless morphing between no poles (dry) and 4-poles (24db per octave). An additional output saturation stage helps keeping the possibly massive resonances in check (it can still get nasty though, you have been warned).

[More information](http://www.airwindows.com/holt)

## Hombre <a id="hombre"></a>

Texas tone and texture

![Rackwindows Hombre](res/images/hombre_panels.jpg)

[More information](http://www.airwindows.com/hombre-vst)

## Interstage <a id="interstage"></a>

Subtle analogifier

![Rackwindows Hombre](res/images/interstage_panels.jpg)

Well, I won't attempt to describe or even explain what this one does. Please head straight over to the Airwindows site for details. But I will say this: If I had to choose just one Airwindows tool, this would be it (or maybe Console?). It's simple, it's subtle and to my ears pure class. Put it anywhere in your patch, you can do no wrong. It will most likely be for the better :-)

[More information](https://www.airwindows.com/interstage/)

## MV <a id="mv"></a>

Dual-mono reverb

![Rackwindows MV](res/images/mv_panels.jpg)

A reverb based on Bitshiftgain and old Alesis Midiverbs. Capable of turning everything into a pad or sustaining a 'bloom' forever. Watch your volume when using small amounts of depth with full on regeneration.

[More information](http://www.airwindows.com/mv)

## ResEQ <a id="reseq"></a>

Resonance equalizer

![Rackwindows ResEQ](res/images/reseq_panels.jpg)

ResEQ passes audio through up to four adjustable frequency bands - and only those bands. All bands are similar and with identical range, but interact with each other in a particular way. They can be stacked for massive boosts or thin the signal out if set slightly apart. What sounds artificial in isolation, can be useful to highlight certain characteristics of a sound and then blend to taste with the dry/wet for more natural results.

[More information](https://www.airwindows.com/reseq-vst/)

## Tape <a id="tape"></a>

All-purpose tape mojo

![Rackwindows Tape](res/images/tape_panels.jpg)

Tape is Airwindows' attempt to capture the very essence of what running audio through tape machines does to the signal. Driving it not only alters the volume, but also applies certain characteristics which are often associated with tape. The bump control allows to adjust the low end.

[More information](http://www.airwindows.com/tape)

## Tremolo <a id="tremolo"></a>

Organic pulsating thing

![Rackwindows Tremolo](res/images/tremolo_panels.jpg)

Instead of volume animation Tremolo uses fluctuating saturation and antisaturation curves to create a more organic, somewhat tubey tremolo effect.

[More information](http://www.airwindows.com/tremolo-vst)

## Vibrato <a id="vibrato"></a>

FM Vibrator o_O

![Rackwindows Vibrato](res/images/vibrato_panels.jpg)

Make sure to also play with the 'Inverse/Wet' knob for chorusing and flange effects. Two trigger outputs have been added for fun.

[More information](http://www.airwindows.com/vibrato-vst)

## A word on processing quality

Most modules feature an **Eco** mode in order to reduce CPU usage on weaker systems. The actual algorithms remain untouched, but any noise shaping/dithering is skipped. This can result in speed improvements of roughly 10% to 50% depending on the module.

## Building from Source

To compile the modules from source, see the official [VCV Rack documentation](https://vcvrack.com/manual/Building.html).

## Colophon

The typeface used on the panels is [Barlow](https://github.com/jpt/barlow) by Jeremy Tribby.