##### Script Introduction:

These scripts enable batch hydrolysis of a large number of proteins and acquisition of relevant parameters, by utilizing the selenium （>=4.11.2) , pandas (>=1.1.5) and some Python basic modules.

The script called ***1-Get the A parameter from Biopep-UMW.ipynb***  implements access to protein A parameters.

And the script called ***2-Collected the Hydrolysate and Antioxidant parameters.ipynb*** could obtained the proteolytic product and some evaluation parameters such as AE，W and DHT.

Additional, the ***tool.ipynb*** provide some relevant data processing functions.

##### Data Introduction：

The folder ***PP*** stores six classes of *Porphyra* proteins collected from the Uniport database. 

The folder ***PPsample*** stores 30% protein sequences of various types of *Porphyra* randomly sampled from *PP*, which were used in my study and put into BIOPEP-UMW for enzymatic simulations, hydrolysis of peptide predictions, hydrolysis of AOP predictions and evaluation of related parameters, such as A, W, AE, DHT.

The results of these proteins are saved in the folder ***results***.
