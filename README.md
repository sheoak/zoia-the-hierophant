# The Hierophant - The Akashic Delay

# Overview

The Hierophant, aka "The Akashic Delay" is a mono-to-stereo delay patch that
transcends genres. Designed with both beginners and experienced players in mind,
it offers a clear and intuitive interface for crafting your sound. Its built-in
overdrive adds warmth and grit to your delays, opening a world of creative
possibilities.

Inspired by the concept of the Akashic Records, an energetic library said to
hold the imprint of all existence, The Hierophant Akashic Delay is always
listening and ready to echo your previously played sound.

# TL;DR (Too Long;Didn’t read)

If you don’t want to go through the documentation and just wanna quickly try out
the patch, I got you cover!

- It’s mono (L) to stereo
- You can find 95% on what you need on first page (parameters and status)
- Bottom pads are menus, (check the visual documentation)
- Second page will give you the 5% you may need (extra parameters)
- Switches and Parameters: look at the visual documentation

# Features

Let's delve into the features that make The Hierophant identity:

- **Akashic Record**: The Akashic Delay is permanently listening in the
  background and will have existing echoes when activated.
- **High-resolution delay time**: For precise adjustments, the delay time
  parameter becomes more responsive at slower settings, allowing for
  fine-tuning.
- **The Confessional:** Mute the incoming signal while allowing existing echoes
  to linger, ideal for creating atmospheric textures with the delay recitation.
  Note that it also disable the Akashic Record memory if you use it when the
  delay is off.
- **Post-Filter:** Sculpt the delay output with a versatile filter, offering
  low-pass, band-pass, and high-pass options with adjustable resonance and
  frequency. Use an innovative radio menu to change the filter, or an external
  footswitch.
- **Smart Tap:** Easily set the delay time with the tap tempo or take over using
  the dedicated parameter.
- **Beat Sync Mode:** Synchronize the delay using MIDI clock or tap tempo for
  tight rhythmic integration. Create "rewind/forward" tape effects or glitches
  by turning this mode on and off.
- **Heretic Overdrive:** Inject warmth and saturation into your delayed sounds
  with the pre-delay overdrive section.
- **Recitation Boost**: Temporary give the recitations (feedback) a kick!
- **Smooth Transitions:** Eliminate unwanted audio jumps with configurable fade
  times when switching the delay on or off.
- **Intuitive User Interface:** Access and adjust key settings on the front page
  for immediate sound exploration. Access an inovative radio menu for more
  control over parameters.
- **Pre-defined MIDI Mapping:** Effortlessly map The Hierophant's controls to
  external devices for hands-free tweaking.
- **Comprehensive Control Center:** Customize footswitch behavior and functions
  for a personalized playing experience with a dedicated configuration page.
- **Signal Chain Enhancements:** Fine-tune your sound with pre-overdrive boost,
  post-overdrive "Purfication" (sort of a soft limiter) for level control and
  dynamic range management.

# Patch structure

The patch is organized in 3 parts :

- **Front Panel (Page 0):** This is your command center, think of it as the
  pedal layout. Offering all the essential controls for immediate sound
  exploration.
- **Customization (Pages 1-3):** Dive deeper here to personalize footswitch
  behavior, configure additional MIDI connections (non CC), or adjust default
  extra settings.
- **Internal Pages (Advanced):** Reserved for experienced users who want to
  modify the patch's core architecture.

# Usage

## Getting started

A straightforward guide ensures you're up and running quickly:

- **Input/Output:** Connect your instrument to the left channel and speakers to
  the stereo output (mono output results in poor sound quality).
- **Operational Mode:** The Hierophant operates in auxiliary mode. Press the
  middle and right footswitches together to activate if in bypass mode.
- **Front Panel:** Explore the essential parameters for sound sculpting, all
  visually represented with clear color-coding in the first page of the patch.

## Front Panel overview

The Hierophant's front panel provides a wealth of real-time control over its
various effects. It’s composed of:

- **Indicators:** Provide visual feedback on effect, filters and mode status.
  Think of a pedal’s leds.
- **Parameters (red):** Dedicated knobs and buttons for delay, overdrive, filter
  and in/out volume. Think of a pedal’s knobs.

It also features two innovatives radio menu (Think a pedal multi-switch):

- **Beat Sync sub-division:** allows you to select the clock divider or
  multiplier for Beat Sync Mode configuration.
- Filter type: allows you to select the filter type or disable it.

Let's delve into each section:

### Indicators

- Center of the left cross:
  - Off: delay is **off**.
  - Yellow: delay is **on**.
  - Yellow, blinking: delay is synchronized to the tap tempo or midi clock,
    blinking in time with the BPM and choosen sub-division.
- Bottom of the left cross: (also act as a clock menu):
  - Yellow: free time (sync off). The delay uses the given “Delay time”
    parameter.
  - Aqua: using tap tempo for synchronization (Sync On, no MIDI clock found)
  - Purple: receiving MIDI clock for synchronization (Sync On)
- **Center of the right cross:
  - Off (no light): Overdrive is **off**.
  - Yellow: Overdrive is **on**
- Bottom Of the right cross (also act as the filter menu):
  - Yellow: No filter applied (Filter Type: None)
  - Peach: Lowpass filter selected
  - Green: Bandpass filter selected
  - Blue: Highpass filter selected

Tips: to remember the colors order, think of earth color (low, peach), grass
(middle, green), and sky (blue)

Additionaly, the “Confessional” and the "Recitation Boost" features will display
the letter "C" and "F" respectively when activated (magenta).

### Parameters

**Delay (Left Cross):**

- **Delay Time:** This parameter controls the echo repetition rate. Its behavior
  depends on the chosen Beat Sync Mode (see section below).
- **Recitation (feedback):** Adjusts the number of times the delayed signal
  repeats itself. Higher values create more repetitions, but be cautious with
  extreme settings. Ensure your output volume remains under control.
- **Dry/Wet:** blends the original (dry) signal with the processed (wet) delayed
  signal. A setting of 0 gives only the dry signal, while 1 provides just the
  delayed sound. Experiment with different ratios to find your sweet spot.
- **Modulation Rate:** Controls the speed of the delay time modulation
- **Modulation Depth:** Sets the intensity of the modulation effect on the delay
- Sync division (last pad at the bottom): opens a menu to select the sync
  division type. On the left: if you want to divide the clock by 2 (bottom), 3
  (middle), 4 (top). On the right if you want to multiply the clock by 2
  (bottom), 3 (middle), 4 (top). Click on the menu button again to keep the beat
  sync to the clock (no division).

  If Beat Sync Mode is on, the indicator will blink to the choosen division.

**Overdrive (Right Cross, Top):**

- **Heresy:** controls the amount of overdrive applied to the signal. 0 bypasses
  the overdrive entirely, but the signal still passes through the circuit.
  Higher values introduce grit and saturation.

**Filters (Right Cross, Bottom):**

- **Cutoff Frequency:** This parameter determines the specific frequencies
  affected by the chosen filter type. The effect on the sound will vary
  depending on your filter selection.
- **Resonance:** Controls the emphasis of the filter's effect at the cutoff
  frequency. Higher resonance creates a more pronounced "peak" in the filtered
  sound.
- Filter type (last pad at the bottom): opens a menu to select the filter type.
  The menu will appear on the right. From top to bottom: LPF (peach), BPF
  (green), HPF (blue). Click on the menu again to disable the filter (yellow).

**Levels (Right Cross, Left and Right):**

- **Level / Boost In:** This knob controls the pre-overdrive boost level. It
  remains active even when the overdrive is bypassed.
- **Level / Boost Out:** This knob adjusts the pre-output boost level, right
  before the signal leaves the ZOIA.

**Important Note:** In ZOIA, the neutral position (100%) for these level
controls translates to a value of 0.8334. Anything above this setting will boost
the signal and potentially cause distortion. Experiment carefully to find the
optimal balance for your needs.

## Beat Sync Mode

The Hierophant offers two primary modes for tailoring your delay behavior: Beat
Sync On and Off. The key difference lies in how the "Delay Time" parameter and
the tap tempo will behave. Beat Sync Mode can be toggle with middle switch long
press.

**Sync Off (Independent Operation):**

- **Bottom Left Indicator:** Yellow
- **Behavior:** Operates independently of all tempo sources
- **Delay Time (top of left cross):** This parameter directly sets the delay
  time, giving you full manual control.
- **Tap Tempo:** If received, the tap tempo (middle switch) will override any
  previously set “Delay Time” value. However, adjusting the “Delay Time”
  parameter after a tap will reset the tap tempo, ensuring your manual
  adjustments take priority. Note that the parameter actually keeps its given
  value position in the front panel. This allows you to play around with "time
  jumps" using the tap tempo and switching back to manual back and forth.

**Sync On (Synchronized Operation):**

- **Bottom Left Indicator:** Aqua (Tap Tempo), or Purple (MIDI clock is running)
- **Behavior:** Synchronizes the delay with an external tempo source (e.g., your
  DAW, synthi phone…) or the tap tempo if no clock is found.
- **Delay Time:** This parameter will be ignored and the clock divider menu will
  be used. If you turn off Beat Sync, the parameter will be use again, which may
  create a “tape rewind” effect (see Patches Ideas section).

By default, the delay will use the clock beat as “time” value. You can choose a
different value using the radio menu, at the bottom of the left cross:

1. click on the menu (might be yellow, aqua, or purple depending on status, see
   above):
2. 6 new pads illuminate. Left side are the clock dividers and right side the
   multipliers.
3. Click on the choosen divider or multiplier. Click on the menu again to use
   default (clock beat)

The values are from top to bottom: 4 (blue), 3 (green), 2 (peach)

## Stomp Switches

Left switch:

- short press (latch): delay on/off
- long press (hold): “Confessional” is open. The delay keeps playing but the
  input bypass the delay. This allows to keep the delay’s “recitation” as a
  background or even as a drum machine. A “C” appears in magenta in the front
  panel.

Middle switch:

- short press: tap tempo. Sets the delay tempo manually by tapping the switch in
  rhythm. See “Beat Sync Mode”.
- long press (latch): sync on/off. If the delay is on, the left cross indicator
  will start blinking if sync is on.

Right switch:

- Short press (latch): overdrive on/off
- Long press (hold): boost the recitation until release. A “F” appears in
  magenta in the front panel.

External footswitch: cycle through different variable filters (Off, lowpass,
bandpass, highpass). The right bottom indicator will change color accordingly
(yellow, green, pink, blue). You can remap it to left or right foot switch (see
customization - controls)

# Customization

Pages 1, 2 and 3 allow you to personnalize The Hierophant. Don’t forget to save
the patch!

## Settings (page 1)

This page lets you adjust settings to your liking:

- **Smooth Delay:** This controls the fade-in and fade-out time for the delay
  effect when switching it on or off. Adjust this setting to achieve the desired
  transition smoothness. 0 means no transition, 1 means 12 seconds transition.
- Heresy output: If the overdrive is too loud when activated, you can lower it’s
  output gain with this parameter.
- Absolution: The overdrive output is send to a compressor set as soft limiter .
  You can control the limit with this parameter. Value 0 means no effect, 1 is
  -30db limiter.
- Boost duration: how long the Recitation Boost takes to go to full level. 0 is
  instant, 1 is 5 seconds. (it uses a CV filter internally)

## Controls (page 2)

The Hierophant lets you tailor its behavior to your playing style by remapping
the functions of the left, middle, and right stomp switches.

**Layout:**

- The panel is divided into three columns, each representing a footswitch.
- Triggers (Top): These define when the action occurs. Note that middle switch
  has no “hold” version.
- Actions (Bottom): Choose the desired function for each footswitch, with
  default color-coded options for easy pairing. Blue is for the external
  footswitch default.

## Connexions (page 3)

This page give you quick access to some common MIDI additionnal triggers and
external footswitch. Note that for control change (CC) parameters, it’s
recommended to use the “starred” menu of the Zoia (shift + star icon). Useful
parameters have been already added to the starred list. Common MIDI CC code are
pre-mapped in the patch.

Default:

- External footswitch to “Next Filter”
- Expression pedal to modulation depth
- Pitch Bend: unmap, to avoid conflict with synthetizers. Suggestion: map to
  delay time
- Midi channel pressure: unmap to avoid conflict. Suggestion: modulation depth

Remember to save the patch!

Exemple:

- To use your expression pedal to modulate the dry/wet value, remove the
  connexion from the “Ext Switch” (right) and connect it to “Dry/wet” on page 0.
- You can add a “midi note” module with velocity output and map its output to
  “Modulation rate” or anything you’d like to control from you velocity
  sensitive MIDI controller.

## MIDI Control (starred list)

You can customize incoming MIDI CC parameters by using the Zoia starred menu.
See Zoia documentation on how to use it if needed.

These are the default values. (Standard midi function is in parenthesis):

- CC 5 (portamento) : Delay fade duration
- CC 7 (Volume MSB) : Output level/boost
- CC 11 (Expression MSB) : Delay modulation depth
- CC 12 : Heresy level
- CC 16 : Delay Time
- CC 17 : Recitation level
- CC 18 : Delay modulation rate
- CC 71 : Cutoff Resonance
- CC 74 : Cutoff Frequency
- CC 86 : Absolution level
- CC 87 : Input level/boost
- CC 91 (reverb level): Delay dry/wet level

To configure pitch bend, expression pedal and external footswitch, see
“connexions”.

Modulation wheel (CC 1) is not map by default to avoid conflict with
synthetizers. Suggestion: Recitation level.

Remember to save the patch after updating mappings!

# Patches Ideas

Here are some patches ideas to get you started with the Hierophant! Your
creations are appreciated, feel free to share in the comment section!

## Slapback delay

This is a popular delay type known for its short, single echo that sits just
behind the original dry signal. It adds a subtle thickening and dimension to
your sound, evoking a vintage rockabilly or surf music vibe.

```
+------------+-------+
| Delay Time | 0.35  |
| Dry/Wet    | 0.65  |
| Recitation | 0.30  |
| Mod Depth  | 0     |
+------------+-------+
| Filter     | Off   |
| Beat Sync  | Off   |
+------------+-------+
```

## Hands-off

Unplug your instrument and unleash The Hierophant's potential! Feed it any sound
source, then explore the evolving textures by tweaking the filter resonance and
delay time with a high recitation. Turn the beat sync mode on and off for
additional effects!

```
+------------+---------+
| Delay Time | 0.62    | 
| Dry/Wet    | 1.0     |
| Recitation | 0.97    |
| Mod. Rate  | 150.00Hz|
| Mod. Depth | 0.10    |
| Frequency  | 758.00Hz|
| Resonance  | 0.1     |
+------------+---------+
| Filter     | LPF     |
| Beat Sync  | On/Off  |
+------------+---------+
```

## Nostalgic

Retro Lushness: Crank up the modulation depth for a thick, warbling chorus
effect. It's perfect for adding a nostalgic touch to your chords and
transporting you back in time.

```
+------------+---------+
| Delay Time | 0.23    |
| Dry/Wet    | 0.6     |
| Recitation | 0.4     |
| Mod. Rate  | 83.99Hz |
| Mod. Depth | 0.3     |
| Frequency  | 758.00Hz|
| Resonance  | 0.1     |
+------------+---------+
| Filter     | Off     |
+------------+---------+
```

## The Hierophant

My first patch before the release, so it deserve to be the Eponym, I guess? Just
try it! Made for the guitar.

```
+------------+----------+
| Delay Time | 0.6490   |
| Dry/Wet    | 0.2243   |
| Recitation | 0.6182   |
| Mod. Rate  | 121.47Hz |
| Mod. Depth | 0.1099   |
| Frequency  | 4928.00Hz|
| Resonance  | 0.2808   |
+------------+----------+
| Filter     | LPF      |
+------------+----------+
```

# Known issues

## Midi clock “running” after unplugging MIDI cable

The sync indicator might show the MIDI clock as 'running' even after unplugging
the cable. This is a visual issue and doesn't affect how the delay syncs. Always
stop the clock on your device before unplugging the MIDI cable. Simply reload
the patch if you experience this issue.

# Technical guide

This section caters to experienced ZOIA users and developers who want to explore
the inner workings of The Hierophant. It delves into the patch's internal
structure, providing access to modify its core functionalities.

**Not essential for basic use:** If you're simply interested in playing and
exploring the sounds of The Hierophant, you can safely skip this section. The
patch is designed to be functional and enjoyable right out of the box.

**For the Curious:** If you're eager to learn more about ZOIA architecture or
want to customize The Hierophant to a deeper level, this section provides the
necessary information

## Signal Path

The patch takes MONO in (left) and output STEREO. The overdrives affect both the
direct signal and the delay. The filter, however, only impacts the sound coming
out of the delay. The “level in” parameter is applied at the start of the chain,
providing a boost. It uses a mixer output gain internally. I will try to update
this section

## How it works

I'm currently finalizing a detailed explanation of The Hierophant's inner
workings but this is not my current priority. If you're eager to learn more, let
me know in the comments below!

# Feedback

I'm always looking for ways to improve my Zoia patches. Feel free to share your
thoughts and suggestions on the patch comments section on Patchstorage or by
sending me a private message on Discord. I appreciate your feedback, especially
regarding the limiter and overdrive settings to optimize the sound quality

# Next…

This patch is hopefuly

# **Thank you!**

The Hierophant wouldn't be here without the incredible ZOIA community. I'd like
to express my sincere gratitude to:

- **Christopher H. M. Jacques:** For his invaluable online resources and
  inspiring patch creations.
- **Barbie Almalbis:** Whose groovy patches ignited the spark for this creation.
- **The Ever-Growing ZOIA Community:** Thank you all for your contributions and
  fostering a space for creative exploration!
