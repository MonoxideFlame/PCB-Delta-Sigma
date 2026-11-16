# Objective:

To design a second order PCB Delta sigma modulator (Takes a low bandwidth, high resolution signal, and converts it to a high bandwidth low resolution signal. ).



It simulates in LT SPICE providing an output of 70dB SNR, at a 2KHz Bandwidth. 

In Lab it tests similarly, though I haven't been able to create a good testing environment for it. 




# Motivation:

This was originally developed with a single ended op-amp in mind, however, I wanted much better Power supply rejection. It was too difficult to measure the performance. 

Now, it has been made more robust with a fully differential mode output. It also helps with signal a  integrity issues. I also added an LDO to keep the noise as minimal as possible. 

As a PCB level design, there are issues when it comes to what one can hope to achieve. Sigma Delta converters see a lot of use at the Die level because it is easier to use a low amount of power,
and keep noise levels equally low. Longer traces, with more capacitance and singal integrity issues mean that I will never be able to achieve the resolution and bandwidth product that the typical 
Sigma Delta Converter will achieve. 

This was mostly a didactic project. Undertaken to familiarize myself with board level design paradigms. 

# Contributors:

Mentor: Dr. William Paul Swartz. 





