# devine
### PI: Gustavo V Cezar.

DEVINE is a SLAC project studying + demonstrating the impact of electric vehicle integration in non-residential environments.

The first analytic piece of the project studied transformer aging in a parking lot of workplace EV charging. The code from this analysis is captured in 'Transformer_Aging', including some of the plotting scripts used to create the results shown in the paper. This is mainly the work of Siobhan Powell.

The market / economic / demand response piece of analysis in DEVINE will be contained in 'Demand_Response_Analytics'. This is mainly the work of Michaela Levine.

The EVSE / charging station modeling piece of analysis in DEVINE is partly contained in 'EVSE_Modeling'. This is mainly the work of Owen Ahlborn.


### Steps to commit `jupyter notebook/lab files - .ipynb`

After you are done with changes in your `.ipynb` run this command in one of the cells:

`!jupyter nbconvert --to script FILENAME.ipynb`

where `FILENAME` is the name of your notebook/lab file. Push both files, `.ipynb` and `.py`.
