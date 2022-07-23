Model Plugin for Orbinaut Framework
    Version:               1.0.0
    Made for Orbinaut ver. 2 - 3.01

Credits
    Concept and Programming: John-Kun (@John-Kun, @John-KunAlt)
    
    Model System: TheSnidr
    
    Model Glitch Fix: MicG (@MichaelGallinago)

    SpecialRing Model: Sonic Mania Devs

Developer Notes
    Hello! Thanks for Downloading this!
    WARNING Normal Draw event break the palette shader, let it blank and use Draw End instead
    if you gonna use this, please credit us who made this.
    
    TheSnidr
    John-Kun
    MicG
    

Installation
    When you gonna import this to your project, First go to "Framework->Create" 
    and add after the instance_create(x, y, Background) you add this, instance_create(x, y, Models); 
    for making the model always spawn in the rooms.
    later go to "Framework->Game Start->Window Startup" and delete the "surface_depth_disable" code,
    or else your models gonna get glitched, later go on Stage->Draw Gui End, there you gonna have IgnoreList, place "Models,"
    after the "Framework ,", and after that you can use this.
