# MXenes4HER
The development of low-cost and highly-efficient pathways to produce renewable energy resources has been one of the top priorities in the science community. To that end, the holistic evaluation and the breathtaking success of MXenes have gained intense momentum by unlocking several new directions toward its usage in catalysis due to their evolutionary hallmark properties. However, the large variety of chemical compositions makes it highly difficult to screen appropriate materials. Hence, it is an urgent need to discover properties that provide information about the catalytic activity at a lower computational cost, particularly to screen over a pool of chemically related family of materials. With this aim, we establish a robust and more broadly applicable multistep workflow from the toolbox of supervised machine learning (ML) algorithms to construct well-trained data-driven models for predicting the hydrogen evolution reaction (HER) activity over 4,500 $MM{^\prime}XT_2$-type MXenes, where 25% of the material space (1,125 systems) is randomly selected to evaluate the HER performance using density functional theory (DFT) calculations.

<img src=ML_workflow.jpg>

# Contents
**MXenes2Code.ipynb** <br>
We provide a step-wise procedure to predict the Gibbs Free Energy (target property) of the hydrogen adsorbed MXenes. The list of all the features are available in **dataset.csv** file and the DFT calculated Gibbs Free Energy of 1,125 MXenes are given in **deltaG_H.csv**, which are used in training the model. 

**MXenes2Model.zip** <br>
The best models (final RFR and GBR models) can be found in the zip folder Models4MXenes, that can be further used for prediction of $MM{^\prime}XT_2$-type MXenes providing the selected input features (key descriptors).

**Code4Plots.ipynb** <br>
Code for designing all the plots are provided here.   

**Dependencies** <br>
The following python libraries have been used in the current work:
1. Pandas &emsp;&emsp;&emsp;4. Seaborn
2. Scikit-learn  &emsp; 5. Re
3. Matplotlib &ensp;&emsp;6. Joblib

**Corresponding Authors** Jayant K. Singh, B. Moses Abraham, Prosun Halder, Priyanka Sinha <br>
**Contact Details** <br>
Email address: jayantks@iitk.ac.in <br>




