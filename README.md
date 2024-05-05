# CPSC 179 Final Project: Belousov-Zhabotinsky Reaction

The BZ chemical oscillator can be modeled as a 3-chemical reaction-diffusion system, based on the following chemical equations: 

A+B -> 2A, at a rate of 𝛼
B+C -> 2B, at a rate of 𝛽
C+A -> 2C, at a rate of 𝛾

My goal was to create interesting patterns beyond the spiral waves and concentric rings of the basic BZ model. While I initially thought I could do this purely with interactive features, such as allowing the user to add more chemicals, adjust the chemical concentrations, and adjust the reaction rates, these did not always produce the most interesting results. In particular, the system would often revert to the basic patterns very quickly. While I did implement at least some version of every proposed model/feature, I have not included videos of them here. 

In the end, I had to modify the system so that the chemicals diffused at differing rates, and I used the Laplacian operator to do so, instead of a simple averaging filter from previous versions. I also coded a wrap-around border, and I combined multiple user interaction features. Visually, my best results were symmetric with a shrinking ‘picture frame,’ as you can see below, and they still involved the spiral patterning that characterizes BZ reactions. 

For more information, please see the linked PowerPoint presentation. You can find background about the BZ model, a detailed explanation of my process, some of the less interesting and/or intermediate video results, and specific parameter values for each implementation.
