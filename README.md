## Vaccine simulation

*This is a personal/university project and it is by no means to be taken as a guideline for governmental optimal policy. Oh, and get vaxxed if you have not.*

This repository contains a jupyter notebook and relative data with which I tried to answer in February 2021 - beginning of vaccination campaign in Italy - whether it would have been more effective to vaccinate young people or elderly people. The model for the epidemic spreading it is taken from [[1]](#1).

To model the various age-specific infection rates I assumed a linear model depending on the average number of contacts per individual of each age category. I used [[2]](#2) and [[3]](#3) to model the contact matrix.

The simulation indeed predicted that administering the vaccine to elder people first is a wise choice in terms of saved human lives.

## References
<a id="1">[1]</a> 
Lavine, Jennie S., Ottar N. Bjornstad, and Rustom Antia. "Immunological characteristics govern the transition of COVID-19 to endemicity." Science 371.6530 (2021): 741-745.

<a id="2">[2]</a> 
Mossong, Joël, et al. "Social contacts and mixing patterns relevant to the spread of infectious diseases." PLoS medicine 5.3 (2008): e74.

<a id="3">[3]</a> 
Jarvis, Christopher I., et al. "Quantifying the impact of physical distance measures on the transmission of COVID-19 in the UK." BMC medicine 18.1 (2020): 1-10.