# Problem Statement
This case study focuses on the detection of malicious URLs, approached as a multi-class classification problem. The goal is to classify raw URLs into one of several categories: benign (safe), phishing, malware, or defacement. Since machine learning algorithms require numeric inputs, we will transform raw URLs into numeric lexical features, which will serve as input for the classifiers. Lexical features are derived from the URL's structure and content, as discussed in various forums such as StackOverflow.

### Three prominent boosting machine learning classifiers will be utilized for this task:

XGBoost
Light GBM
Gradient Boosting Machines (GBM)
# Data Overview
The dataset used for training and testing consists of 651,191 URLs, distributed across four classes:

428,103 benign URLs
96,457 defacement URLs
94,111 phishing URLs
32,520 malware URLs
