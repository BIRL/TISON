The boolean network rules, cell fate classification, mutations files, and fixed input nodes states has been adapted from the work of Cho et al. 2016 (Reference: Cho S-H, Park S-M, Lee H-S, Lee H-Y, Cho K-H. Attractor landscape analysis of colorectal tumorigenesis and its reversion. BMC Syst Biol. 2016;10(1):96.).

To upload this case study, the user must use the 'Import Therapy' button (explained in the Therapeutics Editor User Manual) to upload the network and drug file. Then the deterministic analysis must be performed using the provided cell fate classification file. 

Folders:-
 
02_Description: Contains a .txt file with the network name, network type and analysis type.

03_Network: Contains a .csv network file for this case study which is a rules-based 'Human Signaling Network' with boolean rules

04_Drugs Data: Contains .txt files for drugs used in each analysis of the therapy. 

05_Parameters: Contains a .csv file with the max iterations, heuristic search, and number of states used for this network analysis.

06_Fixed Nodes States: Contains a .csv file with the fixed nodes states for the network.

07_Cell Fate Classification: Contains a .csv file which has all the cell fates associated with the nodes as given in the network of Cho et al. to study Colorectal cancer (CRC) progression in 'Human Signaling Network'.

08_Sample Results: Contains a .csv sample result files for Deterministic Analysis which is performed in TISON's Therapeutics Editor using the aforementioned parameters, fixed nodes states file and cell fate classification file.