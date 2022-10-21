# BluerPlusFirmware

These files were taken directly from the TwoTrees website. I went to help someone else find them and they were no longer in the downloads section for the BLU-5 or Bluer Plus.

Note, I downloaded both because the first one did not work with my printer. The first indicator was that my Z axis was inverted. I have no idea how to identify which file you need. If you have an inverted Z axis in the firmware you loaded. Grab the other and flash it.

## Fixing wonkey Z axis movement

Another note - once I had the right firmware, the Z steps were off and my prints were stretched to be quite tall. I had to double the value in the config. Once unzipped, I opened the cfg file and changed the steps to look like:
```
>DEFAULT_X_STEPS_PER_UNIT	160	#XÖáÄ¬ÈÏÂö³å (steps/mm)	
>DEFAULT_Y_STEPS_PER_UNIT	160	#YÖáÄ¬ÈÏÂö³å (steps/mm)	
>DEFAULT_Z_STEPS_PER_UNIT	400	#ZÖáÄ¬ÈÏÂö³å (steps/mm)	
```

The files uploaded are original download files. I have not adjusted anything in the configuration of these ahead of time because it's my understanding that there may be multiple versions of the printer out there

Feel free to ask questions. I'll do my best to answer whatever I can.
