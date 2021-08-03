# Iot-abnormal-detection
A program of abnormal detection via machine learning and MLP

# Introduction


A large number of IoT devices and cloud servers are currently directly exposed to the Internet. The vulnerabilities in these devices and cloud servers, if exploited, can lead to security risks such as device control, user privacy leakage, data theft from cloud servers, and even serious impacts on the underlying communication networks. 
To facilitate security research in the field of IoT, researchers have produced the UNSW-NB15 dataset, an IoT-based network traffic dataset with different classifications of normal activities and malicious attacks. Based on this dataset, this paper will apply typical techniques in AI, including decision trees, random forests, logistic regression, and multi-layer perceptrons, for detection, in the hope that masters can understand the typical processes of AI techniques applied to security, including data pre-processing, data transformation, and cross-validation, as well as enhance new understanding of IoT security.


# Dateset


The dataset used in this case is UNSW-NB15, an IoT-based network traffic dataset created by the IXIA PerfectStorm tool at the University of New South Wales Canberra Cyber Range Lab to generate a hybrid dataset of real modern normal activity and synthetic contemporary attack behavior. They use the tcpdump tool to capture 100 GB of raw traffic (e.g. Pcap files).
The dataset has nine types of attacks, namely Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode and Worms, which of course have been organized for your convenience, with the features and tags counted into a csv file.
A part of this dataset is used as training set and testing set, i.e., UNSW_NB15_training-set.csv and UNSW_NB15_testing-set.csv. The number of records in the training set is 175,341 and the number of records in the testing set is 82,332, respectively, from different attack types, malicious and normal data.
