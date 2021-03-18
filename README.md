[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/5286)

# Blood-brain barrier (BBB) predictor:

Classifier that will predict if a chemical coumpound will pass the blood-brain barrier.
SBNB lab (IRB Barcelona) - Nov 2020.

USAGE: BBBpredictor myfile.tsv [SMILES or INCHI]

Where myfile.tsv is an input text file that contains two columns separated by TABS.
COLUMN 1: compound unique id (ex:1 or a molecule name without tab characters inside).
COLUMN 2: compound SMILES string.

NOTE: The default format is SMILES and can be set to InChI if the second argument INCHI is provided.
NOTE: Lines starting with '#' as well as empty lines are ignored.

OUTPUT: tsv file containing the prediction for each compound.

PREDICTION LEGEND: the molecule pass the BBB?

0: no

1: yes

-1: the molecular signature could not be calculated for this coumpound


