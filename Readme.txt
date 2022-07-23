Hello! Thanks for Downloading this!

WARNING don't draw models on normal draw event or else the palette will not work

When you gonna import this to your project, First go to "Framework->Create" and add after the instance_create(x, y, Background) you add this,
instance_create(x, y, Models); for making the model always spawn in the rooms.
later go to "Framework->Game Start->Window Startup" and delete the "surface_depth_disable" code,
or else your models gonna get glitched, later go on Stage->Draw Gui End, there you gonna have IgnoreList, place "Models,"
after the "Framework ,", and after that you can use this.

if you gonna use this, please credit us who made this.

TheSnidr
John-Kun
MicG
