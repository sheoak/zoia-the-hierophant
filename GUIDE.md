# Technical Guide

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

See [schema.md].

## How it works

I'm currently finalizing a detailed explanation of The Hierophant's inner
workings but this is not my current priority. If you're eager to learn more, let
me know in the comments below!
