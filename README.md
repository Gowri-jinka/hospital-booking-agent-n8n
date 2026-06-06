# Hospital Appointment Booking Automation using n8n

## Project Overview

This project automates the hospital appointment booking process using n8n. Patients can submit their details through an online form, and the workflow automatically processes the request, stores the information in Google Sheets, assigns an appointment date, and sends a confirmation email.

The workflow integrates Google Gemini AI, Google Sheets, and Gmail to create a complete appointment management system without writing extensive code.

---

Live Demo

Users can access the appointment booking form using the link below:

Appointment Form:

https://firstn8ntask.app.n8n.cloud/form/35189fc7-073d-4fc9-afd6-fcf1e158f44e

Demo Workflow
Open the appointment form.
Enter:
Full Name
Mobile Number
Email Address
Required Service
Submit the form.
Data is automatically processed by Google Gemini AI.
Patient details are stored in Google Sheets.
Appointment date is automatically assigned.
A confirmation email is sent to the patient. 

---
## Features

### Patient Registration Form

Patients can submit:

* Full Name
* Mobile Number
* Email Address
* Service Required

  * General Checkup
  * Orthopedic
  * Dental Checkup

### AI-Powered Processing

* Google Gemini AI processes appointment requests.
* Automatically handles patient information.
* Generates appointment details.

### Automated Appointment Scheduling

* Appointment date is automatically assigned.
* Date is generated 7 days after form submission.

### Google Sheets Integration

Patient details are automatically stored in Google Sheets:

| Name | Mobile Number | Email | Service | Appointment Date |
| ---- | ------------- | ----- | ------- | ---------------- |

### Email Notifications

A professional confirmation email is automatically sent to the patient containing:

* Patient Name
* Selected Service
* Appointment Date
* Appointment Instructions

---

## Workflow Architecture

Form Submission
↓
Google Gemini AI Agent
↓
Google Sheets (Store Patient Data)
↓
Gmail (Send Confirmation Email)

---

## Technologies Used

* n8n Workflow Automation
* Google Gemini AI
* Google Sheets API
* Gmail Integration
* Cloud-based Form Handling

---

## Screenshots

### Appointment Form

(Add screenshot here)

### Workflow Design

(Add screenshot here)

### Google Sheets Data Storage

(Add screenshot here)

### Appointment Confirmation Email

(Add screenshot here)

---

## Automation Flow

1. Patient opens the appointment form.
2. Patient enters personal details.
3. Form is submitted.
4. AI Agent processes the request.
5. Data is stored in Google Sheets.
6. Appointment date is generated automatically.
7. Confirmation email is sent to the patient.

---

## Sample Appointment Email

Subject: Appointment Confirmation

Hello Patient,

Thank you for submitting your appointment request.

Your appointment has been successfully scheduled.

Appointment Details:

* Patient Name
* Service
* Appointment Date

Please arrive at least 15 minutes before your appointment.

Regards,
Appointments Team

---

## Learning Outcomes

Through this project, I learned:

* Workflow Automation using n8n
* AI Agent Integration using Google Gemini
* Google Sheets Automation
* Gmail Automation
* No-Code/Low-Code Development
* Real-world Healthcare Workflow Design

---

## Future Enhancements

* Doctor availability management
* SMS notifications
* WhatsApp integration
* Appointment cancellation and rescheduling
* Admin dashboard
* Patient history tracking

---

## Screenshots

## WORKFLOW
<img width="1919" height="967" alt="workflow" src="https://github.com/user-attachments/assets/f4000386-4377-44fa-be90-77e3cc7469cf" />


## APPOINTMENT FORM
<img width="873" height="946" alt="appointment-form" src="https://github.com/user-attachments/assets/c0dfb443-7241-4924-b504-32b8fea3d6b3" />


## CONFIRMATION-MAIL
<img width="646" height="804" alt="confirmation-email" src="https://github.com/user-attachments/assets/38efb14a-9e51-4373-8eaa-3dec2f035861" />


## GOOGLE SHEET
<img width="1919" height="969" alt="google-sheet" src="https://github.com/user-attachments/assets/28c42aea-068e-4409-b123-6cfc63479e4c" />
