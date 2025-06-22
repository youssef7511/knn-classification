# knn-classification
 what i did :/
 1. Download the Delivery.xls dataset.
2. Install the necessary libraries with the command: pip install openpyxl xlrd
3. Load the dataset using the pandas read_excel function. The
dataset contains the following variables:
- GEST: Gestational age (in weeks) at study entry.
- DILATE: Cervical dilatation (in cm).
- EFFACE: Cervical effacement (in %).
- CONSIS : Cervical consistency (1 = soft, 2 = medium, 3 = firm).
- CONTR: Presence (1) or absence (2) of contractions.
- MEMBRAN: State of membranes (1 = ruptured, 2 = intact, 3 = uncertain).
- AGE: Patient's age.
- STRAT: Period of pregnancy.
- GRAVID: Gestité (number of previous pregnancies, including the current one).
- PARIT: Parity (number of previous full-term pregnancies).
- DIAB: Presence (1) or absence (2) of diabetes, or missing value (9).
- BEBAGE: Gestational age of baby at birth (in days).
- TRANSF: Transfer (1 = yes, 2 = no) to a hospital for specialist care.
- GEMEL: Type of pregnancy (1 = single, 2 = multiple).
- PREMATURE: Target variable indicating whether or not the birth was premature.
4. Display general information about the dataset:
- General structure
- Number of rows and columns
- Types of data
5. Calculate and display descriptive statistics for the variables.

6. Display the distinct values of the variable PREMATURE and visualise the distribution
of the associated observations using a countplo

