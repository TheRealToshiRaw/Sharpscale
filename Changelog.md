# Changelog

2020-06-13 v1.5.0
- Texts in the configuration app has been changed for clarity
- Configuration app has a manual that can be opened from the LiveArea
- kernel plugin does not need to be updated

2020-06-09 v1.4.0
- Allow enable HD framebuffer sizes on the Vita
- Add HD resolutions to scaling test
- Fixed crashes in config app
- Bilinear filtering reverts to system default whenever scaling is not applied

2020-05-05 v1.3.0
- Added an option to enable large framebuffer sizes, when the application uses large framebuffers

2020-04-24 v1.2.0
- Added options for PS1 aspect ratio modes
- Added fitted scaling mode
- Added config application (ur0:/data/sharpscale/config.txt no longer needed)

2020-04-09 v1.1.1
- Fixed a bug where some PS1 games had black screen in 1080i
- Centred the framebuffer when cropping occurs
- Enabled "display area settings" in original mode

2020-04-06 v1.1.0
- All framebuffer sizes are now supported and there are now two configurable options, scaling mode, and bilinear filtering.  
Configuration is provided by a text file at ur0:/data/sharpscale/config.txt.
