#### Script Introduction:

This script ***Rule of five.ipynb*** enables the prediction of drug-like properties for a large number of compounds, including molecular weight, lipid-water partition coefficient, number of hydrogen-bond acceptors, number of hydrogen-bond donors, uptake, rotatable bonds, and more.

In here，pandas (=1.1.5), numpy (=1.19.2) and rdkit (2021.09.4) were used and number of drug-like principles reached by the compound were evaluated.

According to the Lipinski principles of drug-like substances and their supplements, a good drugable molecule should have a molecular weight of less than 500 Da, a lipid-water partition coefficient of less than 5, an HBA of less than 10, an HBD of less than 5, an ingestibility of less than 30%, a rotatable bond of less than 10, and a large QED.

#### Data Introduction:

In here, the decoy gotten from DUD-E server  were stored in ***decoy.csv*** as the inputted file. And the result from the script were exported in ***decoy_ro5.csv***.