# COMPGI10 Coursework
Predicting the subcellular location of eukaryotic proteins
Within the last few years the complete sequence has been determined for over 3000 genomes. This has created the need for fully automated methods to analyse the vast amount of sequence data now available. The assignment of a function for a given protein has proved to be difficult where no clear homology to proteins of known function exists. Knowing the subcellular location of a protein (i.e. where in the cell it is found) in may give some clue as to its possible function, making an automated method that assigns proteins to a certain subcellular location a useful tool for analysis.

For eukaryotes, it is reasonable to define 4 major subcellular locations:

Cytosolic - i.e. within the cell itself, but not inside any organelles

Secreted - proteins which are transported out of a cell

Nuclear - proteins found/used within the cell's nucleus

Mitochondrial - proteins transported to the cell's mitochondria


Your task in this coursework is to develop a simple method for classifying eukaryotic protein sequences into the 4 categories above.

You are free to use any appropriate machine learning technique for this task - e.g. neural nets, SVMs, decision trees - whatever you like. THIS IS NOT A SOFTWARE ENGINEERING CLASS, so you are free to use off-the-shelf machine learning methods or libraries e.g. Matlab or LIBSVM as long as you give enough information for someone to replicate your approach. Any method that you develop should be SELF-CONTAINED, however. It should not rely on external web services or even require a working internet connection to run it on a new sequence - you should in theory be able to just hand someone a USB stick with all the code and data needed to run your method on their own machine with nothing else required, other than e.g. a working Matlab installation. You should also try to select open-source tools and libraries wherever possible (though again use of Matlab is acceptable).

Predictions must be returned along with some measure of confidence. This can be a probability estimate or even an ad hoc measure of confidence e.g. HIGH, MEDIUM, LOW. You must explain the basis of your confidence estimates.

Appropriate cross-validation studies should be carried out on the datasets. Details on the selection of test and training sets must be given in the write-up, and appropriate measures of success must be given e.g. % correct assignments, correlation coefficients. Results for the "blind" protein set must be included in the report.

The method and its evaluation must be written up as a report in the style of a short bioinformatics paper. Although you are quite free to use other formats, you might like to use the templates for the Bioinformatics journal itself. See HERE. Supplementary materials e.g. source code can also be submitted as an appendix to the paper. In your paper you should introduce the problem, discuss reasons for selecting the method you did, describe the method and the experiments you have carried out, present the results, discuss the results and give your conclusions.

Assessment will be mostly aimed at the quality of the report and the correctness of the evaluation rather than the success of the method. However, bonus marks may be awarded for especially successful or particularly creative approaches. However, don't sweat blood to come up with the most sophisticated possible approach!
