# **BLASTgffextractor**

The script is intended to extract portions of a  GFF annotation file based on the output from BLAST.

Usage: blastgffextractor1-0.py BLASToutputfile GFFfile output.csv

BEFORE THE START, YOU MUST REMOVE THE GFF STANDARD HEADER AND INPUT A NEW ONE (tab delimited!!!):

Cromossomo    Genbank    regiao    pbinicio    pbfim    .    +    .    annotation

Example:

![image](https://user-images.githubusercontent.com/105673165/168724377-984f871c-e6d1-4870-8515-8f525d054689.png)

*just like that!

(you can adapt it if you want. If so, remember to change the columns names in the loop lines of the code).

You ALSO NEED a header to the BLAST output file:
      
Sequence chromosome id seqsize num1 num2 num3 seqsize2 bpbegin bpend e-value num4 (tabdelimited!!!)""")