The weight-based network, mutations files, and cell fate classification has been adapted from the work of Choi et al. (Reference: Choi M, Shi J, Jung SH, Chen X, Cho K. Attractor Landscape Analysis Reveals Feedback Loops in the p53 Network That Control the Cellular Response to DNA Damage. 2012;5(November)).

To upload this case study, the user must use the 'Import Therapy' button (explained in the Therapeutics Editor User Manual) to upload the network and drug file. Then the deterministic analysis must be performed using the provided cell fate classification file. 

Folders:-

02_Description: Contains a .txt file with the network name, network type and analysis type.

03_Network: Contains a .csv network file for this case study which is a weight-based 'p53 Network with DNA damage OFF'. The file contains node basal values and node interactions. 

04_Drugs Data: Contains .txt files for drugs used in each analysis of the therapy. 

05_Parameters: Contains a .csv file with the max iterations, heuristic search, and number of states used for this network analysis.

06_Cell Fate Classification: Contains a .csv file which has all the cell fates associated with the nodes as given in the network of Choi et al. to study the 'p53 Network' in MCF-7 cell lines.

07_Sample Results: Contains a .csv sample result files for Deterministic Analysis which is performed in TISON's Therapeutics Editor using the aforementioned parameters and cell fate classification file.