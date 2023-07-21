
Technische Universität Wien, Security, Privacy and Explainability in ML

## Anonymisation & Record-linkage Attack
### 
##### Fani Sentinella-Jerbić, Ana Terović, 2023


This repository contains the code and resources for performing k-anonymization and record-linkage attack on the [Adult Census dataset](https://archive.ics.uci.edu/dataset/2/adult) obtained from the [UCI Machine Learning repository](https://archive.ics.uci.edu/). The dataset includes sensitive information such as income level, age, education level, marital status, occupation, race, and gender.


#### K-Anonymization
k-anonymization is a privacy-preserving technique that ensures each record in a dataset cannot be distinguished from at least k-1 other records with respect to certain identifying attributes. By applying this technique, we aim to protect individuals' privacy while still maintaining the utility of the dataset.

#### Record Linkage Attack

To evaluate the effectiveness of the k-anonymization technique, we conducted a record-linkage attack on both the k-anonymized datasets and an arbitrarily anonymized dataset. The goal of a record-linkage attack is to identify individuals in an anonymized dataset by linking records across multiple datasets using various attributes.

### Findings

Based on our experiments and analysis, we have observed that non-Quasi-Identifiers (non-QIs) can pose significant challenges in data anonymization. They can have highly specific values, making them susceptible to one-to-one mapping attacks, especially for outliers. Additionally, attackers with general or background knowledge about the data can exploit this information to link records and potentially re-identify individuals.

