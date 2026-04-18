<!--
  SEO KEYWORDS: Innoze, Innoze Tech, Innoze Tech Solutions, InnozeTech,
  innoze github, innoze tech github, innoze tech solutions github, 
  Healthcare Management System, Doctor Appointment Booking, Clinic Management System,
  Hospital Management System, Digital Prescription System, Patient Management Pakistan,
  MERN Stack Healthcare, React Healthcare App, Online Doctor Booking Pakistan,
  Appointment Booking System, Prescription Management, Patient History Tracking,
  Full Stack Healthcare Platform, Telemedicine Platform Pakistan, Clinic Software Pakistan,
  Innoze, Innoze Tech, Software House Pakistan, hospital-management-system,
  clinic-management-system, doctor-appointment-booking-system, healthcare, prescription-management
-->

<div align="center">

<h1>🏥 Prescripto — Smart Healthcare Management System</h1>

<p>A production-ready, full-stack <strong>Clinic & Hospital Management Platform</strong> built by <strong><a href="https://github.com/innozetech">Innoze</a></strong> — with dedicated portals for Patients, Doctors, and Admins to manage appointments, digital prescriptions, and patient history in real-time.</p>

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-Visit_Site-F5C518?style=for-the-badge&logoColor=black)](https://prescripto-frontend-eosin.vercel.app)
[![Built by Innoze](https://img.shields.io/badge/Built_by-Innoze-D4A017?style=for-the-badge&logoColor=black)](https://github.com/innozetech)
[![Status](https://img.shields.io/badge/Status-Live_&_Running-success?style=for-the-badge&logoColor=white)](https://prescripto-frontend-eosin.vercel.app)

</div>

---

## 🎯 The Problem

Most clinics and hospitals in Pakistan still rely on:

- ❌ Manual appointment books & phone calls — leading to double bookings and no-shows
- ❌ Paper prescriptions — easily lost and impossible to track
- ❌ No patient history records — doctors start fresh every visit
- ❌ No admin oversight of doctors and appointments
- ❌ Zero digital presence — patients can't book online 24/7
- ❌ No secure system for patient data and records

---

## ✅ Our Solution

**Innoze** built a complete three-sided healthcare platform — **Patients** book appointments and view digital prescriptions, **Doctors** manage appointments and write prescriptions, and **Admins** oversee the entire clinic operation — all from one seamless system.

> A clinic can now run its entire operation digitally — no phone calls, no paper, no confusion.

---

## 💼 Business Impact

| Before | After |
|:-------|:------|
| Appointments booked via phone calls | ✅ 24/7 self-service online booking |
| Paper prescriptions get lost | ✅ Digital prescriptions — always accessible |
| No patient history tracking | ✅ Complete history with full edit trail |
| No-shows waste doctor time | ✅ Slot-based booking with OTP verification |
| No admin oversight | ✅ Real-time dashboard with full platform stats |
| No data security | ✅ JWT auth + bcrypt encryption |

---

## ✨ Key Features

### 🧑‍⚕️ Patient Portal
- 🔐 Secure registration, login & OTP-based password reset
- 🆔 Auto-generated unique Patient ID for every patient
- 👨‍⚕️ Browse doctors by 6 specialities with availability status
- 📅 Slot-based appointment booking (30-minute slots, 10 AM – 9 PM)
- 📋 View & cancel appointments
- 💊 View complete digital prescriptions issued by doctors
- 📱 Fully responsive — mobile, tablet & desktop

### 🩺 Doctor Portal
- 📊 Personalized dashboard — earnings, appointments & patient count
- 📋 View, complete & cancel appointments
- 💊 Write detailed digital prescriptions with:
  - Diagnosis & Symptoms
  - Medicines & Instructions
  - Lab Tests & Next Visit date
- ✏️ Edit prescriptions with full edit history tracking
- 🗂️ View complete history of all treated patients
- 👤 Manage profile, fees & availability status

### 🛡️ Admin Portal
- 📈 Platform dashboard — total doctors, appointments & patients
- ➕ Add, edit & manage doctors with photo upload
- 📋 View & cancel any appointment on the platform
- 🗂️ View completed appointment history
- 🔑 Dual login — Admin & Doctor from same panel

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|:------|:-----------|
| **Frontend** | React 19, Vite, Tailwind CSS, React Router |
| **Backend** | Node.js, Express.js 5 |
| **Database** | MongoDB Atlas, Mongoose |
| **Auth** | JWT, bcrypt, OTP via Nodemailer |
| **Media Storage** | Cloudinary |
| **Email** | Gmail SMTP via Nodemailer |
| **Deployment** | Vercel |

</div>

---

## 📸 Project Screenshots

### 🧑‍⚕️ Patient Portal

<table>
  <tr>
    <td align="center">
      <img src="./screenshots/register.PNG" alt="Register" width="100%"/>
      <br/><b>📝 Register</b>
    </td>
    <td align="center">
      <img src="./screenshots/login.PNG" alt="Login" width="100%"/>
      <br/><b>🔐 Login</b>
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <img src="./screenshots/herosection.PNG" alt="Home" width="100%"/>
      <br/><b>🏠 Home — Hero Section</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./screenshots/browserdoctorbyspecliaity.PNG" alt="Browse Doctors" width="100%"/>
      <br/><b>👨‍⚕️ Browse Doctors by Speciality</b>
    </td>
    <td align="center">
      <img src="./screenshots/appointmentbooking.PNG" alt="Book Appointment" width="100%"/>
      <br/><b>📅 Appointment Booking</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./screenshots/myappointment.PNG" alt="My Appointments" width="100%"/>
      <br/><b>📋 My Appointments</b>
    </td>
    <td align="center">
      <img src="./screenshots/Digitalprescription.PNG" alt="Digital Prescription" width="100%"/>
      <br/><b>💊 Digital Prescription</b>
    </td>
  </tr>
</table>

### 🩺 Doctor Portal

<table>
  <tr>
    <td align="center">
      <img src="./screenshots/doctorlogin.PNG" alt="Doctor Login" width="100%"/>
      <br/><b>🔑 Doctor Login</b>
    </td>
    <td align="center">
      <img src="./screenshots/doctordashbaord.PNG" alt="Doctor Dashboard" width="100%"/>
      <br/><b>📊 Doctor Dashboard</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./screenshots/appointmentlist.PNG" alt="Appointments" width="100%"/>
      <br/><b>📋 Appointments List</b>
    </td>
    <td align="center">
      <img src="./screenshots/patienthistory.PNG" alt="Patient History" width="100%"/>
      <br/><b>🗂️ Patient History</b>
    </td>
  </tr>
</table>

### 🛡️ Admin Portal

<table>
  <tr>
    <td align="center">
      <img src="./screenshots/Adminlogin.PNG" alt="Admin Login" width="100%"/>
      <br/><b>🔑 Admin Login</b>
    </td>
    <td align="center">
      <img src="./screenshots/admindashboard.PNG" alt="Admin Dashboard" width="100%"/>
      <br/><b>📈 Admin Dashboard</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./screenshots/adddoctor.PNG" alt="Add Doctor" width="100%"/>
      <br/><b>➕ Add Doctor</b>
    </td>
    <td align="center">
      <img src="./screenshots/doctorlist.PNG" alt="Doctor List" width="100%"/>
      <br/><b>👨‍⚕️ Doctors List</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./screenshots/allappointment.PNG" alt="All Appointments" width="100%"/>
      <br/><b>📋 All Appointments</b>
    </td>
    <td align="center">
      <img src="./screenshots/appointmenthistory.PNG" alt="Appointment History" width="100%"/>
      <br/><b>🗂️ Appointment History</b>
    </td>
  </tr>
</table>

---

## 🌟 Why Innoze Built This

At **Innoze**, we engineer solutions that solve real-world problems. Prescripto was built to bring Pakistani clinics and hospitals into the digital age — replacing paper, phone calls, and manual processes with a **secure, scalable, and intelligent healthcare platform**.

> This project demonstrates our capability to build **multi-role, enterprise-grade systems** with complex business logic, secure authentication flows, and clean modern UI/UX.

---

## 🤝 Want This System for Your Clinic or Hospital?

<div align="center">

> Need an appointment booking system, patient management platform, or custom healthcare solution?
>
> **Innoze is here to build it, design it, and grow it with you.**

<br/>

[![Email Us](https://img.shields.io/badge/📩_Email_Us-info.innoze@gmail.com-F5C518?style=for-the-badge&logoColor=black)](mailto:info.innoze@gmail.com)
&nbsp;
[![Visit Innoze](https://img.shields.io/badge/🏢_Visit_Innoze-innozetech-D4A017?style=for-the-badge&logo=github&logoColor=black)](https://github.com/innozetech)

</div>

---

<div align="center">
  <sub>Built with ❤️ by <strong><a href="https://github.com/innozetech">Innoze</a></strong> — Karachi, Pakistan 🇵🇰</sub>
</div>
