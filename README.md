# RNA SEQ ANALYSIS ON ENDOMETRIAL CANCER
Endometrial cancer, a common gynecological malignancy, involves the abnormal growth of cells in the uterus lining. As its occurrence continues to increase and its various molecular subtypes become more apparent, delving into the molecular intricacies of endometrial cancer becomes vital for improving how we diagnose and treat this condition. In this exploration, we dive into the intricate world of endometrial cancer, looking not just at the disease itself but also at the various molecular patterns it presents. By understanding these patterns, we hope to contribute to a better understanding of patterns and relationships within endometrial cancer.
Endometrial cancer data utilized in this study were obtained from Dr. Enrique Velaquez's lab at the University of Southern California. A total of five samples were collected from the lab, and an additional five controlled samples were sourced from the National Center for Biotechnology Information (NCBI). The criteria for selecting controlled samples from NCBI were based on availability and relevance to endometrial cancer research. From Dr. Velazquez’s lab samples, there were three Black-African American samples and 2 White samples. More specific patient demographics, clinical details, or selection criteria for the samples collected from Dr. Enrique Velaquez's lab is not available. Supplementary data from a study conducted by Dr. Zonngao Shi titled “RNA-seq Reveals the Overexpression of IGSF9 in Endometrial Cancer” were integrated into the analysis. This dataset included controlled samples, contributing valuable information to the overall exploration. Using an online database for the controlled samples helps with cost-effectiveness and since this is an exploratory data analysis this helps gain insight on patterns and relationships. Two RNA-seq analyses were performed with one focusing on the difference between the different groups of race. RNA seq count files were provided for both the collected and controlled sample sets. These analyses were conducted using the DESeq2 package in R. 
Through the first analysis compared the five samples collected and the five controlled samples adjusting for race. The top GO terms from the analysis were: 
1. GO:0005515 - Protein binding
2. GO:0005737 - Cytoplasm
3. GO:0050794 - Regulation of cellular process
4. GO:0048518 - Positive regulation of biological process
5. GO:0048522 - Positive regulation of cellular process
6. GO:0005829 - Cytosol
7. GO:0031982 - Vesicle
8. GO:1901564 - Organonitrogen compound metabolic process
9. GO:0005654 - Nucleoplasm
The top downregulated genes were: ENSG00000007038, ENSG00000107159, ENSG00000120068, ENSG00000120075, ENSG00000125730, ENSG00000145284, ENSG00000156689, ENSG00000162174, ENSG00000163283 and ENSG00000163739 with a total of 23 genes. The top ten upregulated genes were ENSG00000007952, ENSG00000009765, ENSG00000012504, ENSG00000050628, ENSG00000053438, ENSG00000064886, ENSG00000069482, ENSG00000074211, ENSG00000075043 and ENSG00000075891 with a total of 40 genes. These did not match all of the same top GO genes, downregulated and upregulated genes found in existing literature. This could be due to the limited sample size. Larger datasets could provide more context similar to existing literature on patterns associated with endometrial cancer. 
The second analysis done on the endometrial cancer did not adjust for any variables. The top ten GO terms for the analysis were: 
1. GO:0034330 - Cell junction organization
2. GO:0034329 - Cell junction assembly
3. GO:0010817 - Regulation of hormone levels
4. GO:0071944 - Cell periphery
5. GO:0005576 - Extracellular region
6. GO:0007043 - Cell-cell junction assembly
7. GO:0015020 - Glucuronosyltransferase activity
8. GO:0046873 - Metal ion transmembrane transporter activity
9. GO:0065008 - Regulation of biological quality
10. GO:0032501 - Multicellular organismal process
The top ten downregulated genes were ENSG00000007038, ENSG00000107159, ENSG00000120068, ENSG00000120075, ENSG00000125730, ENSG00000145284, ENSG00000156689, ENSG00000162174, ENSG00000163283 and ENSG00000163739. There were a total of 9779 downregulated genes.  The top ten upregulated genes were ENSG00000000419, ENSG00000001084, ENSG00000001167, ENSG00000001629, ENSG00000001631, ENSG00000002745, ENSG00000003056, ENSG00000003393, ENSG00000003509 and ENSG00000003756. There were a total of 6290 upregulated genes. These did not match all of the same top GO genes, downregulated and upregulated genes found in existing literature. 
The code used is provided in other parts of the repository. Data collected is not shown as it is collected directly from Dr. Velazquez’s lab. 
