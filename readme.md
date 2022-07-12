# Arkhn Data Practical challenge 

## Introduction
This challenge is handed out to the candidate a few days before meeting with our team in-person. 
In this document we provide context, general guidelines about the expected deliverables and data material on which this challenge is based. 
The candidate is free to use any tool and programing language of his or her choice. 

During the in-person interview, the candidate will present his or her work, argue the technical choices made
and discuss potential challenges faced. This will feed a follow-up discussion on topics related to the challenge.

If the candidate judges that any part of this challenge requires clarification, he or she is welcome to reach out via e-mail. 



## Materials 

This challenge is based on two sources of data : 
- [MIMIC-III](https://mimic.mit.edu/docs/iii/), Medical Information Mart for Intensive Care III, a freely available database made from deidentified EHR data. 
- A .csv file containing patient data manually gathered by clinicians.


### Database credentials 
``` 
 host : **
 port : 5432
 user : *
 password : * 
 database : mimic
 ```
*user and password will be shared separately. 

### Clinical data manually gathered
See ``manual_data.csv`` file. 


## Deliverables

The candidate is asked to provide a self-contained and sustainable solution to help physicians
study some constants of their patients during their stay. Some attention to performance is expected.    
The physicians targeted are anesthetists or resuscitators.
The vital signs they are interested in are : Blood Pressure, SpO2, Heart Rate, Respiratory Rate and can be any other relevant observation proposed by the candidate.
This data must be monitored with regard to patient demographic data (id, gender, age, medical comments). 
Physicians expect to be alerted when these levels reach critical values. 
Finally, they also expressed the need to access the content of patients prescriptions easily. 

* Analytics Engineers candidates: 
It is expected from Analytics Engineer candidates' solution to monitor not only patients from the ``manual_data.csv`` file, but also any patient of the database.

* Healthcare Data Anlaysts candidates:
It is expected from Healthcare Data Analysts candidates' solution to only monitor the patients from the ``manual_data.csv`` file. Of course, you can tackle the data of more patients if you want.

## Extra
Other laboratory measurements to monitor : Alk Phosphate, Calcium, Epoetin alfa. 

```
NB: Even though we expect results as support to the discussion, we also care about the approach
 and the arguments underlying the choices made by the candidate.
```
