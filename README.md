Protein_Database


This project is an implementation based on Article [1]. The method
is based on the rapid identification of small structural patterns. Two complex structures
that share a sufficient number of small motives in common, will be considered likely to
similar. This method thus resembles the word bag techniques that are used for textual documents.

This repo was used to create a protein database, where every protein is represented by a 13-dimension vector, as explained in [1].
Two proteins will thus be considered 'similar' if the norm of their difference is low.   

[1] Xuefeng Cui, Shuai Cheng Li, Lin He and Ming Li, Fingerprinting protein structures effectively and efficiently, 
Bioinformatics, Vol. 30, No. 7, pp 949–955, April 2014.
