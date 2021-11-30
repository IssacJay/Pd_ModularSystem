//Copyright (c) 2021 [Issac Thomas]
// issacthomas.co.uk

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Pd Modular System"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.
-------
INSTALLING 
The modular system was developed in Pd Version 49. Certain libraries are required for some modules. These include: else, cyclone, zexy, and Mr Peach.   

GUIDE TO USE OF MODULAR SYSTEM 

The Modular system has been created for experimental sound design, and to extend the features of Digital Audio Workstations by implementing a graphical and patched based workflow. Using internal sound and MIDI drivers such as Soundflower and the IAC driver, users are able to send audio and MIDI between the Modular system, DAW's and other programmes.

Start by selecting an audio interface- if you are using wanting to pass audio in and out of other programmes then an aggregate device will have to be created that includes an internal sound bus. Also, for MIDI to be passed in and out of the Pure Data then the IAC driver must be turned on (on mac) and the IAC Driver selected in MIDI preferences. All Modules require DSP to be turned on once you are ready to perform.

The system comprises of individual Modules that can be patched together to create interesting sound design and compositions. Modules can be selected from the Modules button on the control panel.

GETTING STARTED WITH PATCHING

Modules are all loaded below the control panel, but it's best to move them and keep that general area clear for loading new modules.

Inlets and outlets are labelled, so that it should be clear what inlets and outlets can be patched together.

The Control Panel contains the Master Clock, Master Out, and Master Save/Recall functions. The master volume slider must be up, as well as the appropriate output channels selected before anything can be heard. The output sends channels can be selected to run audio through an internal audio bus into other programmes. The masterclock sends bangs to modules that use tempo, such as the generative scale. You can choose between an internal BPM, or send a metronome output into Pure Data via an audio channel, and have the patch create a bang based on the Attack of the metronome. This is a good way to combine DAW tempo maps with the System.

SAVING 

The Master Patch must not be altered or renamed, and modules must not be moved from their folders. To create a new patch, the entire Modular System folder should be copied. The folder can be renamed to whatever you want to call it, and a patch can be saved in there, and different samples can be added to the Samples folder. The reason for copying the whole folder, is that the dynamic patching can only be loaded to the patch if it is called "Master_Patch", and also text files are written into the 'modules' folder containing all of the saved parameter information.