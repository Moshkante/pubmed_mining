# pubmed_mining
Term-based text-mining of the PubMed repository.
Requires internet access!

The function takes vectors of string as term sets for fixterms (research topic focus) and pubterms (terms which can pivot around your research focus).
Install the function with devtools::install_github("Moshkante/pubmed_mining")
Mining results are given in text format with pointwise mutual information (pmi-score) and related titles and publishing years.

Example:  
fixterms = c("dog", "cat")  
pubterms = c("behaviour", "clinic", "injuries", "diseases")  
output = YOUR/DESIRED/OUTPUT/PATHWAY (Default = your current directory)  
pubmed_textmining(fixterms, pubterms, output)  
