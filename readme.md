# Analytics Engineer Practical challenge 

## Introduction
This challenge is handed out to the candidate a few days before meeting with our team in-person. 
In this document we provide context, general guidelines about the expected deliverables and data material on which this deliverable should be based. 
The candidate is free to use any tool and programing language of his or her choice. 

During the in-person interview, the candidate will present his or her work, the technical choices made
and discuss potential challenges faced. This will feed a follow-up discussion on topics related to the challenge.

If the candidate judges that any part of this challenge requires clarification, he or she is welcome to reach out via e-mail. 


## Materials 

This challenge is based on two sources of data : 
- [MIMIC-III](https://mimic.mit.edu/docs/iii/), Medical Information Mart for Intensive Care III, a freely available database made from deidentified EHR data. 
- A .csv file containing patient data manually gathered by clinicians.


### Database credentials 
``` 
 host : mammouth.arkhn.com
 port : 5432
 user : *
 password : * 
 database : mimic
 ```
*user and password will be shared separately. 

## Deliverables

The candidate is asked to provide a self-contained and sustainable solution to help physicians (which can be anesthetists or resuscitators) 
monitor the vital signs of their patients (eg : Blood Pressure, SpO2, Heart Rate, Breath Rate, Respiratory Rate and any other relevant observation)
during their stay, as well as some laboratory measurements (eg: Alk. Phosphate, Calcium, Epoetin alfa). This data should 
be monitored with regard to patient demographic data (id, gender, age, medical comments). They should be alerted when these levels are critical. 
Finally, physicians also expressed the need to access the content of patients prescriptions easily to improve care. 