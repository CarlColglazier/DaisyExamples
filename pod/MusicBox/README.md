# MusicBox

Simple Example using VisualGDB extension for Visual Studio.

Pretty much a playground for testing, or creating new vs projects.

This may not always be configured to run on the pod, but should be able to work on all platforms with relatively few changes to any of the code.

Can be built in Visual Studio with MSBuild, or using local Makefile.

# Code Snippet  
```cpp  
//Generates next note
if(hw.button1.RisingEdge())
{
    freq = mtof(48.0f + get_new_note());
    osc.SetFreq(freq);
    env.SetTime(ADENV_SEG_DECAY, dec);
    env.Trigger();
}
```
