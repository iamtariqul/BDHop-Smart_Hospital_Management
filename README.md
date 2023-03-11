# BDHop: Smart Hospital Management for Daffodil International University
This project Smart Hospital Management Application includes the registration of patients, storing their details in the system, and also computerized billing in the pharmacy, and labs. The software has the facility to give a unique id for every patient and stores the clinical details of every patient and hospital tests done automatically. It includes a search facility to know the current status of each patient. Users can search for details of a patient using the id. The Hospital Management System can be entered using a username and password. It is accessible either by an administrator or receptionist. Only they can add data to the database. The data can be retrieved easily. The interface is very user-friendly. The data are well protected for personal use and make data processing very fast.

We will bring our web application and mobile application updates so that there are many more benefits for people to use. We want to fast delivering healthcare model and need to improve management in our hospital or plan to innovate healthcare with new software product. Basically, we want to smart hospital management application so that people can use our web application easier.
# Requirement
xhtml2pdf, Django==3.0.5, django-widget-tweaks==1.4.8, sqlparse==0.3.1

### Admin
- Signup their account. Then Login (No approval Required).
- Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
- Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).
- Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
- Can view/book/approve Appointment (approve those appointments which is requested by patient).

### Doctor
- Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).
- Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.
- Can view their discharged(by admin) patient list.
- Can view their Appointments, booked by admin.
- Can delete their Appointment, when doctor attended their appointment.

### Patient
- Create account for admit in hospital. Then Login (Approval required by hospital admin, Then only patient can login).
- Can view assigned doctor's details like ( specialization, mobile, address).
- Can view their booked appointment status (pending/confirmed by admin).
- Can book appointments.(approval required by admin)
- Can view/download Invoice pdf (Only when that patient is discharged by admin).

![image](https://user-images.githubusercontent.com/72482679/224467110-c57e9289-4d1b-4c0b-86c0-67bc6ca5dceb.png)
![image](https://user-images.githubusercontent.com/72482679/224467121-baa53938-a2a7-41c0-97e9-c5fdc818608d.png)
![image](https://user-images.githubusercontent.com/72482679/224467128-7c6075a2-dd75-4e32-9f14-41ac15baead7.png)
![image](https://user-images.githubusercontent.com/72482679/224467134-f4b749a4-0356-4df7-9ca6-c714239ea922.png)
![image](https://user-images.githubusercontent.com/72482679/224467143-158113dc-7a19-477a-8cdb-2266d85c4eff.png)
![image](https://user-images.githubusercontent.com/72482679/224467145-5c092042-1b32-4146-8942-9f4e4725eb8c.png)
![image](https://user-images.githubusercontent.com/72482679/224467149-c7e0cee3-b2af-4d15-85bd-a1f32e00b5b2.png)
![image](https://user-images.githubusercontent.com/72482679/224467153-33fda2d7-d54b-4c0c-a112-7cc5bb04eb5d.png)
![image](https://user-images.githubusercontent.com/72482679/224467156-f4d16c6c-6ab2-4eef-ade7-ab6df800f23a.png)
![image](https://user-images.githubusercontent.com/72482679/224467165-e23ad0a9-20ac-4ae7-bd11-c8b3609a972e.png)
