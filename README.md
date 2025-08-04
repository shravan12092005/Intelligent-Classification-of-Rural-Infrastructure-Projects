# Intelligent-Classification-of-Rural-Infrastructure-Projects
Machine learning model to classify rural road/bridge projects under the correct PMGSY scheme (PMGSY-I, II, RCPLWEA, etc.) based on physical and financial data. Built using Python and deployed via IBM Cloud Lite. Dataset: AI Kosh - PMGSY
Intelligent Classification of Rural Infrastructure Projects (PMGSY)
This project focuses on classifying rural infrastructure projects under the appropriate PMGSY scheme (e.g., PMGSY-I, PMGSY-II, RCPLWEA) using machine learning techniques. The solution is developed and deployed on IBM Cloud Lite services using structured project data provided via the AI Kosh platform.

Problem Statement
The Pradhan Mantri Gram Sadak Yojana (PMGSY) is a key initiative aimed at improving rural road connectivity across India. Over time, it has evolved through multiple schemes, each with different goals, funding models, and specifications.

Manually classifying thousands of projects into the correct scheme is time-consuming, error-prone, and unscalable. To address this, we propose an AI-based system that can automatically classify road or bridge projects based on their physical and financial characteristics.

Proposed Solution
The system uses supervised machine learning to learn from historical project data and accurately predict the PMGSY scheme classification for new or existing projects.

Key Features:
Automated classification of projects into schemes like PMGSY-I, PMGSY-II, RCPLWEA
Structured input using project length, cost, category, and region
Real-time deployment on IBM Watson Studio with API access
Technologies Used
IBM Watson Studio – For model development and deployment
IBM Cloud Object Storage – For storing and accessing datasets
Python – For data preprocessing and modeling
Scikit-learn / TensorFlow – For ML algorithms
JSON / CSV – Dataset format
AI Kosh – Dataset source
Algorithm & Deployment
Algorithm: Random Forest Classifier (or SVM based on evaluation)
Data Input: Project attributes like cost, length, work category, and state
Training: Supervised learning on labeled PMGSY_SCHEME data
Deployment: IBM Watson Studio, exposed via API for real-time use
Results
The model demonstrated high accuracy in correctly classifying projects into the respective PMGSY schemes and was successfully deployed on IBM Cloud for scalable access and real-time prediction.

Conclusion
The ML-based system enhances the efficiency and accuracy of infrastructure project classification. It supports better decision-making for government bodies, improves transparency in budget allocation, and enables large-scale monitoring of rural development programs.

Future Scope
Expand to other rural development schemes beyond PMGSY
Integrate real-time data from government portals and IoT systems
Apply deep learning (e.g., LSTM) for sequential project analysis
Enable predictive planning and anomaly detection
References
AI Kosh PMGSY Dataset – AI Kosh Link
IBM Cloud & Watson Studio Documentation – IBM Docs
Scikit-learn – https://scikit-learn.org
TensorFlow – https://www.tensorflow.org
Ministry of Rural Development – https://pmgsy.nic.in
Developed by: Rohit Lambole
Institution: MIT Academy of Engineering, Department of Computer Engineering
