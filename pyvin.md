## About my PyVIN research

California as the US state with the largest population, highly variable climate, and vast agricultural exports has extensive agricultural and urban water needs. To complement its high water demand, California has developed a vast water network over the past 100 years, now reaching roughly 700 miles from Shasta Lake in the northern half of the state to the beaches of San Diego. 

The CALVIN model was developed by a team of researchers led by Professor Jay Lund and Professor Richard Howitt to gain insight into this complex water network. More information about the CALVIN model can be found on the [CALVIN website](https://watershed.ucdavis.edu/shed/lund/CALVIN/). 

PyVIN implements the CALVIN network structure with the Python language to create an open source hydro-economic modeling platform utilizing state of the art solvers. My work has been increasing the capabilities of PyVIN, including features to study how climate variability will impact water deliveries statewide and distilling model results to identify systemwide improvements to better prepare California for future droughts. 


### CALVIN Water Network

The Center for Watershed Sciences has developed a handy CALVIN network map which visualizes the entire network and results. For those unfamiliar with California's extensive water system, [this map](https://cwn.casil.ucdavis.edu/) will help contextualize the size and complexity of the PyVIN model.

## EWRI Presentation

I will be presenting my [poster](/other/poster.pdf) at EWRI on Wednesday May 24th from 10:30am-12pm. Come swing by and ask questions!

## Important Github Repositories

[PyVIN repository](https://github.com/msdogan/pyvin) \\
[CALVIN data](https://github.com/ucd-cws/calvin-network-data) \\
[Data export tool](https://github.com/ucd-cws/calvin-network-tools)

## PyVIN Webtool

Downloading the CALVIN data from Github can be a laborious process, so I am developing a webtool where users can fill out a form (example shown below) and submit to an Amazon Web Services virtual machine I manage and it will generate the data file without the need for the user to clone the CALVIN repositories to their desktop or download NodeJS.