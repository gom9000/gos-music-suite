# Music Suite
Personal hub of music-related repositories, organized by category.

This suite represents the fusion of my digital workbench and my musical inclination.  
The projects collected here range from bare-metal firmware designed to make vintage hardware sing, to custom-built boxes for the stage. Alongside completed instruments ready for the gig, there are transcriptions in progress and sawdust of MIDI messages.

---


<br/><img src="resources/banner-box.svg" width="100%" alt="BOX Banner">

>**[MusicalBOX](https://github.com/gom9000/MusicalBOX)**  
>**Type**: MIDI Sampler Player | **Status**: Completed
>
>An audio sample player based on Raspberry Pi. It allows the selection of up to 16 presets via a 2x8 switch matrix and features software-based audio routing to two independent output lines.

>**[MusicalBOX-SM (Stage Module)](https://github.com/gom9000/MusicalBOX-SM)**  
>**Type**: Expander Module | **Status**: Development
>
>An evolution of the original sampler, rebuilt from scratch as a complete stage sound module: mono and stereo samples, layered and split programs, per-program tone and ADSR, configurable effects chain, low-latency C++ engine on Raspberry Pi 4.

>**[DynamicsBOX](https://github.com/gom9000/DynamicsBOX)**  
>**Type**: Volume Control | **Status**: Development
>
> A box designed to control the volume of two audio lines using a standard expression pedal. A PIC microcontroller scans the pedal's potentiometer value and reproduces it on a digital potentiometer, keeping the audio signal physically decoupled from the pedal circuit.

>**[MIDIFilterBOX](https://github.com/gom9000/MIDIFilterBOX)**  
>**Type**: MIDI Filter | **Status**: Development
>
>A utility for real-time manipulation of MIDI streams. It is designed to filter or transform messages between various nodes of a musical setup.


---


<br/><img src="resources/banner-standalone.svg" width="100%" alt="Standalone Banner">

>**[Floppyti - A MIDI Floppy-Drive Music Player](https://github.com/gom9000/floppyti)**  
>**Type**: MIDI Audio Module | **Status**: Completed
>
>A hardware-based MIDI instrument that converts MIDI-IN messages into musical notes by controlling the stepper motor of a standard floppy disk drive. The system features a bare-metal implementation on a PIC 16F628A microcontroller and custom hardware designed to interface the MIDI protocol and the drive's stepper control interface.

>**[The Banks Side of The Genesis](https://github.com/gom9000/the-banks-side-of-the-genesis)**  
>**Type**: Music Sheet | **Status**: Ongoing
>
>A personal archive (working scores for a tribute band) of keyboard transcriptions and study scores for Genesis music. All sheets are written using the LilyPond typesetting system, focusing on the intricate textures of the "Banks side" of the band's discography.

>**[TankYou](https://github.com/gom9000/TankYou)**  
>**Type**: Power Supply | **Status**: Completed
>
>A compact (KH-6 enclosure) 4-line power supply bank (9V-100mA) specifically designed to power audio effect pedals (stomp boxes). It includes polarity testing and a daisy-chain port for additional devices.

>**[TankYou - rev2](https://github.com/gom9000/TankYou-rev2)**  
>**Type**: Power Supply | **Status**: Completed
>
>An advanced version of stomp boxes power supply bank, powered directly by the mains. It features two isolated grounds and four regulated 9V-200mA lines (two per ground), ensuring noise-free operation and stability.


---


<br/><img src="resources/banner-hosted.svg" width="100%" alt="Hosted Banner">

>**[gosDelay - VST Simple Delay Effect](https://github.com/gom9000/gosDelay)**  
>**Type**: VST Effect | **Status**: Completed
>
>A custom VST delay effect developed in C++, offering essential delay control within a DAW environment.


---


## About
**Author**: Alessandro Fraschetti (gom9000).
