#### Scripts Introduction：

These scripts enable batch acquisition of AMDET attributes for a large number of peptides or compounds of interest, automated through the use of the selenium module and the pandas module in Jupyter environment.

One script called ***ADMETobtainedFromadmetlab3.ipynb*** stored in the folder named **ADMETobtainedFromadmetlab3**, which be able to obtain the AMDET properties in admetlab 3.0 website. 

The ***example.csv*** file in the same directory can be used as an input file reference for using the script or as an exercise file, with the results in the ***results*** folder.

This study likewise developed scripts for high volume compound ADMET attribute acquisition for amderSAR 2.0 servers, stored in folder ***ADMETobtainedFromadmetsar2***.

Alternatively, peptides containing specific amino acids, such as S-element-containing amino acids, amino acids with aromatic rings, and hydrophobic amino acids, are recognized by using the script ***Find special Amino Acid.ipynb*** saved in the ***Find special Amino Acid*** folder.

In here, the file ***example.csv*** is provided as an exercise and as a reference file for the input format. Its result stored in file named ***ExampleSaaResult.csv***.

#### Data organisation：

The ADMET data for the *Porphyra* hydrolysed peptides collected in two servers used in this study were stored in two folders called ***admetlab*** and ***ADMETsar***. 

The **Extract ADMET Data.ipynb** script implements the extraction and collection of information needed for these ADMET files.

