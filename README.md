# Characterizing Yeast Osmotic Shock Response with Fluorescence Microscopy 

I worked on this project for fun, as a way to quantitatively analyze 20.309 osmotic shock lab data from when I took the class in Spring 
2024. The lab, based on the <a 
href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2916730/" target="_blank">paper</a> 
<em>The Frequency 
Dependence of Osmo-adaptation in Saccharomyces cerevisiae</em> by Mettetal 
et al., unites control theory with biology to understand how yeast respond 
to changes in salt concentrations in their environment. In this lab, we 
genetically engineered yeast with RFP-labeled Nrd1 (a nuclear protein) as 
well as GFP-labeled Hog1 (a protein overexpressed and localized to 
the nucleus during osmotic shock in order to induce transcriptional 
changes). Using a fluorecence microscope hand-built throughout the 
semester as well as a custom-made microfluidic device, we flowed media 
with fluctuating salt concentrations over yeast cells. Every few minutes, 
we recorded photographs of the yeast. Though not a required part of the 
lab, the ultimate goal—which I have realized through this side project—was to analyze time-dependent trends of Hog1 localization in the nucleus 
via GFP/RFP colocalization seen in these photographs.

As an example, this is one frame of microscopy data. 

<img src='https://github.com/katie-sp/yeast/blob/main/raw.png' width=500vw>

Though contrast is low, my code identifies most of the individual yeast cells, each individually colored for visualization purposes below.

<img src='https://github.com/katie-sp/yeast/blob/main/clusters.png' width=500vw>

Finally, my code analyzes pixel values of each yeast identified over time and plots the variance of the pixel values at each frame, a good approximation for localization of GFP signal over time.

<img src='https://github.com/katie-sp/yeast/blob/main/plot.png' width=500vw>

