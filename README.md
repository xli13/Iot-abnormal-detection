# Iot-abnormal-detection
A program of abnormal detection via machine learning and MLP

# Introduction


A large number of IoT devices and cloud servers are currently directly exposed to the Internet. The vulnerabilities in these devices and cloud servers, if exploited, can lead to security risks such as device control, user privacy leakage, data theft from cloud servers, and even serious impacts on the underlying communication networks. 
To facilitate security research in the field of IoT, researchers have produced the UNSW-NB15 dataset, an IoT-based network traffic dataset with different classifications of normal activities and malicious attacks. Based on this dataset, this program will apply typical techniques in AI for detection, including decision trees, random forests, logistic regression, and multi-layer perceptrons. 


# Dateset


The dataset used in this case is UNSW-NB15, an IoT-based network traffic dataset created by the IXIA PerfectStorm tool at the University of New South Wales Canberra Cyber Range Lab to generate a hybrid dataset of real modern normal activity and synthetic contemporary attack behavior. They use the tcpdump tool to capture 100 GB of raw traffic (e.g. Pcap files).
The dataset has nine types of attacks, namely Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode and Worms, which of course have been organized for your convenience, with the features and tags counted into a csv file.
A part of this dataset is used as training set and testing set, i.e., UNSW_NB15_training-set.csv and UNSW_NB15_testing-set.csv. The number of records in the training set is 175,341 and the number of records in the testing set is 82,332, respectively, from different attack types, malicious and normal data.
The link of the dataset is 
https://research.unsw.edu.au/projects/unsw-nb15-dataset

# Reference
N. Moustafa and J. Slay, "UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)," 2015 Military Communications and Information Systems Conference (MilCIS), 2015, pp. 1-6, doi: 10.1109/MilCIS.2015.7348942.


Moustafa, Nour, and Jill Slay. "The evaluation of Network Anomaly Detection Systems: Statistical analysis of the UNSW-NB15 dataset and the comparison with the KDD99 dataset." Information Security Journal: A Global Perspective (2016): 1-14.
Moustafa, Nour, et al. "Novel geometric area analysis technique for anomaly detection using trapezoidal area estimation on large-scale networks." IEEE Transactions on Big Data (2017).


Moustafa, Nour, et al. "Big data analytics for intrusion detection system: statistical decision-making using finite dirichlet mixture models." Data Analytics and Decision Support for Cybersecurity. Springer, Cham, 2017. 127-156.


Sarhan, Mohanad, Siamak Layeghy, Nour Moustafa, and Marius Portmann. NetFlow Datasets for Machine Learning-Based Network Intrusion Detection Systems. In Big Data Technologies and Applications: 10th EAI International Conference, BDTA 2020, and 13th EAI International Conference on Wireless Internet, WiCON 2020, Virtual Event, December 11, 2020, Proceedings (p. 117). Springer Nature.
