# EBFC
A novel enzyme-based functional correlations algorithm of metabolome-microbiome  
  
**Statement of Use**  
The EBFC software is provided for research purposes only. For commercial use, please contact me at 3119020093@stu.cpu.edu.cn.  
  
**Download**  
Please click the link at https://github.com/EightForest/EBFC/archive/refs/heads/main.zip to download the FNICM software and other files.  
  
**Usage**  
The software doesn’t require installation and simply double-click the ‘EBFC.exe’ to open it. Then you can see the opened window in your desktop.  
![image](https://github.com/EightForest/EBFC/blob/main/images/Figure1.PNG)  
Next, you can easily obtain the results after the following two steps.  
1. Input file: "taxonomy.tsv","EC_predicted.tsv","Micro_abundance.csv","Metab_KEGG_ID.csv","Metab_abundance.csv".
![image](https://github.com/EightForest/EBFC/blob/main/images/Figure2.PNG)  
    "taxonomy.tsv": The file about annotation of the features that were observed in this study by performing taxonomic classification of the sequences, obtained from QIIME2.
  
    "EC_predicted.tsv": The file about predicted functional abundances based only on marker gene sequences, obtained from PICRUSt2.
  
    "Micro_abundance.csv": The file about the abundances based only on marker gene sequences, obtained from QIIME2.  
  
    "Metab_KEGG_ID.csv": The file about the KEGG ID based only on metabolites of interest, obtained from the KEGG database.  
  
    "Metab_abundance.csv": The file about the abundances based only on metabolites of interest, obtained from XCMS.  
  
2. run the program  
Then, you can click the ‘Start’ button to run the program.

3. Output results  
After the program finishes, you can obtain the following one file. These files are stored in the folder named Output_results within the directory where the software is saved.  
![image](https://github.com/EightForest/EBFC/blob/main/images/Figure3.PNG)
