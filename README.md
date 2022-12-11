# ICOT
Interpretable clustering

Here the code and experiments are presented based on the formulation in "Bertsimas, D., Dunn, J. (2021). Interpretable clustering: an optimization approach" with some changes in formulation of MIO. Also the tree was constructed for interpretability of the results.

Code is presented along with experiments on different simulated data sets. 

Remark:
Warm starts have not been implemented yet. Hence ICOT implemented here may be used on data sets of small size and with maximum depth of 2-3. The structure of clusters also has impact on the time of execution: "better" separated clusters provide better performance.
