# Investigate a dataset by python

## Introduction

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

The dataset contains factors per each patient that may help in the investigation.

### Data Dictionary

01- PatientId:
Identification of a patient

02- AppointmentID:
Identification of each appointment

03- Gender:
Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.

04- ScheduledDay:
The day someone called or registered the appointment, this is before appointment of course.

05- AppointmentDay;
The day of the actuall appointment, when they have to visit the doctor.

06- Age:
How old is the patient.

07- Neighbourhood:
Where the appointment takes place.

08- Scholarship;
True of False . Observation, this is a broad topic, consider reading this article
https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia

09- Hipertension;
True or False

10- Diabetes:
True or False

11- Alcoholism:
True or False

12- Handcap:
True or False

13- SMS_received:
1 or more messages sent to the patient.

14- No-show:
True or False. No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

### Questions to answer:
What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

### Libraries Used:
-- pandas
-- numpy
-- matplotlib

### How to Run:
Run using Jupter