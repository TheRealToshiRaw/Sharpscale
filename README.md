# Sharpscale

Sharpscale is a PSTV and PS Vita plugin that changes the framebuffer to display scaling method to provide a cleaner and sharper image.  

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/SRJV9iP2tkY/0.jpg)](https://youtu.be/SRJV9iP2tkY)  
#### ( Preview video from Zodasaur: https://youtu.be/SRJV9iP2tkY )

# Info
This plugin is the only method to obtain native resolution video capture with accurate colours at 60fps.  
&nbsp;&nbsp;A hardware capture kit for the Vita was previously available from Japan for $450 USD,  
&nbsp;&nbsp;but due to changes in Japanese laws, this is no longer available.

This is the first time in history a Vita nuova bounty organised by Rinnegamante has been filled.  

I want to thank the donors ScHlAuChii, eleriaqueen, mansjg, TG,  
&nbsp;&nbsp;as well as the excellent members of CBPS for the support they have provided.

I also want to thank rinne for diligently updating each bounty issue with the bounty total whenever someone else donated.

# Usage:
Sharpscale can be configured to different scaling methods.

Scaling Modes:
  - Original: system default
  - Integer: integer scaling while fitting inside the display, for general use with bilinear filtering off
  - Real: no scaling, for video capture
  - Fitted: non integer scaling fitting exactly inside the display while preserving aspect ratio, 
      for media use with bilinear filtering on, or PS1 with bilinear filtering off

PS1 aspect ratio:
  - Pixel: aspect ratio of the framebuffer is retained
  - 4:3: aspect ratio is forced to 4:3
  - 16:9: aspect ratio is forced to 16:9

Scaling algorithm:
  - Point: nearest neighbour
  - Bilinear: bilinear interpolation (system default)

In Adrenaline, set graphics mode to original in Adrenaline settings.

Unlock framebuffer size:
  - On: allow framebuffers of sizes 1280x720, 1440x1080, and 1920x1080 to be used
  - Off: system default 

# Installation:
	*KERNEL
	  ur0:tai/sharpscale.skprx

# Configuration:
  Use the provided configuration app to change settings instantly without needing reboot or close the foreground application.

# Misc.
If the config app crashes on startup, follow these steps:
1. Use the plugin and config app attached to this post
2. Ensure that the plugin is loaded. It will be immediately noticeable on startup if it is loaded.
3. Disable plugins for the config app by adding the following line
```
*!AKRK00005
```
before this line in the taihen config.txt
```
*ALL
```

# Changelog
See Changelog.md


[Download binary](https://forum.devchroma.nl/index.php/topic,112.0.html) | [Report bugs](https://github.com/cuevavirus/sharpscale/issues) | [Source code](https://git.shotatoshounenwachigau.moe/vita/sharpscale/)
