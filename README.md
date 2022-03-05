<!-- ABOUT THE PROJECT -->
# Master thesis - Assocation rule mining with electronic health records: Exploring comorbidity diagnoses of major depressive disorder 

## About The Project

This study is a master thesis project at the Department of Computer and Systems Sciences of Stockholm University. The aim of this study was to explore comorbidity diagnoses of major depressive disorder by applying association rule mining with the Apriori algorithm on the MIMIC-IV dataset. Patients with primary ICD-10 diagnosis F32.9 (n=6659) and their comorbidities have been identified. An equal number of patients with no major depressive disorder were randomly selected and matched with the experimental group by gender and age group. Frequent itemsets and association rules were generated using a minimum support threshold of 6% and a minimum confidence threshold of 60%. Pearson’s chi-squared (χ2) test was subsequently used to evaluate the statistical significance of the generated association rules.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* Python 3.8.5
* Jupyter Notebook 6.3.0
* pandas
* mlxtend

<p align="right">(<a href="#top">back to top</a>)</p>



## Prerequisites

### Access to MIMIC-IV dataset
* Only credentialed users who sign the specified data-use agreement can access the files. Visit Physionet.org to become a "credentialed user", and sign a data-use agreement.

### MIMIC-IV files saved locally
The following files have to be saved locally:
* `admissions.csv`
* `patients.csv`
* `d_icd_diagnoses.csv`
* `diagnoses.csv`

<p align="right">(<a href="#top">back to top</a>)</p>

## Licence
The default copyright laws apply, meaning that all rights to this source code are retained. The code may not be reproduced, distributed, or derivative works created with it.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Dominic Nicolas Iseli - dois2136@student.su.se

Project Link: [https://github.com/dominiciseli/Master-Thesis](https://github.com/dominiciseli/Master-Thesis)

<p align="right">(<a href="#top">back to top</a>)</p>
