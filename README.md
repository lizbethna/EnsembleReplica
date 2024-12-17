##--------------------------------------------------

Paper: 
A data ensemble-based approach for detecting vocal disorders using replicated acoustic biomarkers from electroglottography  

Authors:
Lizbeth Naranjo (1), Carlos J. Perez (2), Daniel F. Merino (2)

Journal:
Sensing and Bio-Sensing Research Journal, 2025, vol, num, pages.  


(1) Departamento de Matematicas, Facultad de Ciencias, Universidad Nacional Autonoma de Mexico, Ciudad de Mexico, Mexico.
(2) Departamento de Matematicas, Facultad de Veterinaria, Universidad de Extremadura,  Caceres, Spain.

##--------------------------------------------------

Instructions to run the codes in Markdown and R software. 
The codes are applied to obtain similar analysis with cross-validations as in Sections:
5. Simulation-based experiment
6. EGG data-based experiments

##--------------------------------------------------

FOLDERS for section 5. "Simulation-based experiment":

- Data_simulation: code for data simulation process of Algorithm 3.
- RSAM_Simula: codes for Algorithm 1 "RSAM" for 7 different base classification models. 
- FESPAE_Simula: codes for Algorithm 2 "FESPAE" for 7 different base classification models. 


##--------------------------------------------------

FOLDERS for section 6. "EGG data-based experiments":

- Data_EGG_saarbrucken: EGG data for vowels /a/, /i/, and /u/.

- RSAM_EGG_a: EGG vowel /a/, codes for Algorithm 1 "RSAM" for 7 different base classification models. 
- RSAM_EGG_i: EGG vowel /I/, etc.
- RSAM_EGG_u: : EGG vowel /u/, etc.

- FESPAE_EGG_a: EGG vowel /a/, codes for Algorithm 2 "FESPAE" for 7 different base classification models. 
- FESPAE_EGG_i: EGG vowel /I/, etc.
- FESPAE_EGG_u: EGG vowel /u/, etc.

##--------------------------------------------------

To run the files, do the following.
 
1.- Install the packages necessary to run the R files. These are indicated in the R file. 

2.- Change the address indicated in 'address="HERE"' and ‘setwd("HERE")’. 
This is the address where the files are in.

3.- For section 5. "Simulation-based experiment", first run the R file to simulate the data, and then run the R files to estimate the parameters of the  model.

4.- For section 6. "EGG data-based experiments", run the R files to estimate the parameters of the  model.

##--------------------------------------------------

