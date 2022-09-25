# **Show Up or No Show to Appoinments**
----
 
## Introduction ☑ 

  A person makes a doctor appointment, receives all the instructions and no-show. Who to blame? If this help you studying or working, please don´t forget to upvote :). Reference to Joni Hoppen and Aquarela Advanced Analytics Aquarela . Data Content is 110.527 medical appointments its 14 associated variables (characteristics). The most important one if the patient show-up or no-show to the appointment. Variable names are self-explanatory, if you have doubts, just let me know!
 
  In this project , I've apply Data Cleaning , Data Analysis , Data Viusalization to more understand the dataset and finally apply Machine Learning to predict if the 
the patient will show up to appoinments or not with accuarcy 86 % in both of training and testing

  For More Information about Dataset : https://www.kaggle.com/joniarroba/noshowappointments

## Data Columns ⚡
  1. PatientId : Identification of a patient 
  2. AppointmentID : Identification of each appointment
  3. Gender : Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.
  4. DataMarcacaoConsulta : The day of the actuall appointment, when they have to visit the doctor.
  5. DataAgendamento : The day someone called or registered the appointment, this is before appointment of course.
  6. Age : How old is the patient.
  7. Neighbourhood : Where the appointment takes place.
  8. Scholarship : True of False . Observation, this is a broad topic, consider reading this article https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia
  9. Hipertension : True or False
  10. Diabetes : True or False
  11. Alcoholism : True or False
  12. Handcap : True or False
  13. SMS_received : 1 or more messages sent to the patient.
  14. No-show : True or False.


## Final Conclusions ❤
  1. Most of patient people has been showed up to appointments
  2.Patients Females have been shown up to appointments more than Patients Males
  3. The average age of male Diabetics is equal to the average age of female Diabetics
  4. The average age of male Hipertension is equal to the average age of female Hipertension
  5. The average age of male Handicaps is less than to the average age of female Handicaps
  6. Most of Alcoholism are Males
  7. Commen Waiting Days for Patients is from 0 to 25 days
  8. Patients who showup waits from 0 to 30 days
  9. Patients who no-show waits from 0 to 65 days
  10. Average of waiting days for Diabetics and Hypertensive Patients are less than Non-Diabetics and Non-Hypertensive Patients
  11. Most of Patients Don't have Scholarship and Patients having Scholarship 76.26 % of them are been shown up to appointments
  12. There is no relation between receiving SMS and showing up to appointments as most of shown up don't receiving SMS
  13. The highest numbers of appointments are made by Patients in age range between (0 to 10) and (50 to 60)
  14. The five most neighborhoods where patients are shown up to Appointments 're : JARDIM CAMBURI , MARIA ORTIZ , RESISTÊNCIA ,JARDIM DA PENHA and SANTA MARTHA
  15. There are no appointments on Sunday and less appointments is on Saturday
  16. Predicting Show-Up/No-Show Appointments can done using XGboost Model or Gradient Boosting Model
