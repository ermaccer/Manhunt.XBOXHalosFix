# Manhunt.XBOXHalosFix

This is a port of Fire_Head's PC halos fix to XBOX, the issue
is the same as on PC so the fix can be ported without any problems.



# How to use (IPS Patch)

You can install .IPS patch to your executable using [Lunar IPS](https://fusoya.eludevisibility.org/lips/)

**mh_halosfix_pal.ips** - European version

**mh_halosfix_ntsc.ips** - American version
 



# Manual 

If your executable already has some patches, you can manually patch the bytes using any hex editor (I recommend HxD)


## PAL/European

Search for 

`81 C4 24 01 00 00 E9 A5 9A 0A 00 81 C4 20 01 00 00 C3 90 90 90 90 90 90 90 90 90 90 90 90 90 90`

and change to:

`81 C4 04 00 00 00 E8 A5 9A 0A 00 81 C4 20 01 00 00 6A 00 6A 01 E8 D6 D0 FF FF 58 58 C3 90 90 90`

## NTSC/American

Search for 

`81 C4 24 01 00 00 E9 F5 99 0A 00 81 C4 20 01 00 00 C3 90 90 90 90 90 90 90 90 90 90 90 90 90 90`

and change to:

`81 C4 04 01 00 00 E8 F5 99 0A 00 81 C4 20 01 00 6A 00 6A 01 E8 76 D0 FF FF 58 58 C3 90 90 90 90`

[![YouTubeVideo](https://i.imgur.com/H5N798p.jpg)](https://www.youtube.com/watch?v=S3HTgMWLGmI)
<p align="center">Click the image to go to the YT video.</p>
