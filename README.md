# ASIC-Music-Synthesizer
ECE 5746 Applied Digital Asic Design - Virtual Analogue Synthesizer

The purpose of this project is to design and build the envelope (ENV) section of a virtual analogue synthesizer. The ENV block controls the sound's amplitude change over time, which is what allows us to differentiate sounds from each other. The enveloped used for this project is an Attack, Decay, Sustain, Release (ADSR) envelope which takes a sample from the oscillator block (OSC) and modifies it according to which ADSR phase of the envelope the sample corresponds to. This sample then gets sent to the amplifier block (AMP), which then sends it to the Nyquist filter block (NYQ).

An in-depth description of the project can be found in [Link to Final Report](Final_Report.pdf)

Run the Virtual Analogue Synthesizer by running the file synth.m. The output file 'test.wav' will be stored in the corresponding MATLAB directory. All parameters are named according to the ETH Zürich naming convention
