# Cervical-Cancer-Risk-Factor-Analysis
### Machine Learning with Data Visualizations

## Abstract:
Cervical cancer occurs at cervix of women. Cervix is the lower part of the uterus. It is caused by the HPV virus, which can be spread by sexual contact. Most of the time, women's body can fight off the virus by itself, but not all the time. The time when women's body can't fight off the virus, it can leads to cancer. Women can have different kind of medical test such as HPV test to check for abnormality. Cancer can be prevented by treating any problems before they become cancer.

This project looks at a data set of cervical cancer. The purpose is to see what are the risk factors for cervical cancer. Python is used for the analysis. The steps involved in the projects are: data import, data wrangling, EDA, data preprocessing, and modeling. 

## [Data](https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29):
### Meta data:
* Age: Age of patients (Numeric)
* Number of sexual partners: The number of sex partner (Numeric)
* First sexual intercourse: Age of first sexual intercourse (Numeric)
* Num of pregnancies: Number of pregnancies (Numeric)
* Smokes: Whether the smokes or not (Categorical)
* Smokes (years): Number of years the patient smoked (Numeric)
* Smokes (packs/year): A pack year is defined as twenty cigarettes smoked everyday for one year (Numeric)
* Hormonal Contraceptives: Whether the patient used a type of birth control that uses hormones to prevent pregnancy (Categorical)
* Hormonal Contraceptives (years): Number of years that the patient used hormonal contraceptives (Numeric)
* IUD: whether the patient use the IUD (Intrauterine contraceptive device)(A device inserted into the uterus (womb) to prevent conception (pregnancy))(Categorical)
* IUD (years): Number of the years that the patient used IUD (Numeric)
* STDs: Whether the patient diagnosed with a STD (Sexually transmitted disease) (Categorical)
* STDs (number): Number of STDs (Numeric)
* STDs:condylomatosis: Whether the patient diagnosed with condylomatosis (Categorical)
* STDs:vaginal condylomatosis: Whether the patient diagnosed with vaginal condylomatosis (Categorical)
* STDs:vulvo-perineal condylomatosis: Whether the patient diagnosed with vulvo-perineal condylomatosis (Categorical)
* STDs:syphilis: Whether the patient diagnosed with syphilis (Categorical)
* STDs:pelvic inflammatory disease: Whether the patient diagnosed with pelvic inflammatory disease (Categorical)
* STDs:genital herpes: Whether the patient diagnosed with genital herpes (Categorical)
* STDs:molluscum contagiosum: Whether the patient diagnosed with molluscum contagiosum (Categorical)
* STDs:HIV: Whether the patient diagnosed with HIV(Categorical)
* STDs:Hepatitis B: Whether the patient diagnosed with Hepatitis B (Categorical)
* STDs:HPV: Whether the patient diagnosed with HPV (Categorical)
* STDs: Number of diagnosis: Number of the STD diagnoses of the patient (Numeric)
* Dx:Cancer: Diagnosis of cancer (Categorical)
* Dx:CIN: Diagnosis of CIN (Cervical intraepithelial neoplasia) (Categorical)
* Dx:HPV: Diagnosis of HPV (human papilloma virus) (Categorical)
* Dx: Diagnosed or not (Categorical)
* Hinselmann: Hinselman test result (Categorical)
* Schiller: Schiller test result (Categorical)
* Citology: Citology test result (Categorical)
* Biopsy: Biopsy test result (Categorical)

Note:  
Hinselmann is a medical diagnostic test.  
Schiller is a preliminary test for cancer.  
Citology is the examination of cells from the body under a microscope.  
Biopsy is a sample of tissue taken from the body in order to examine it more closely. A doctor should recommend a biopsy when an initial test suggests an area of tissue in the body isn't normal. Doctors may call an area of abnormal tissue a lesion, a tumor, or a mass.

**Categorical Features**: Smokes, Hormonal Contraceptives, IUD, STDs, STDs:condylomatosis:, STDs:cervical condylomatosis, STDs:vaginal condylomatosis, STDs:vulvo-perineal condylomatosis, STDs:syphilis, STDs:pelvic inflammatory disease, STDs:genital herpes, STDs:molluscum contagiosum, STDs:AIDS, STDs:HIV, STDs:Hepatitis B, STDs:HPV, STDs: Number of diagnosis, Dx:Cancer, Dx:CIN, Dx:HPV, Dx, Hinselmann, Schiller, Citology, Biopsy.

**Numerical Features**: Age, Number of sexual partners, First sexual intercourse, Num of pregnancies, Smokes (years), Smokes (packs/year), Hormonal Contraceptives (years), IUD (years), STDs (number), STDs: Number of diagnosis.

### Data issues:
* Missing Data
* Imbalanced Data

## Machine learning models used or tried:
* Random Forest
* Boosted Decision Tree
* Support Vector Machine
* K Nearest Neighbors
* Logistic Regression
* Ridge Regression Classifier
