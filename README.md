
<!-- 🌟 PROJECT BANNER -->
<h1 align="center">🏥 Healthcare Application — Manual Testing Documentation</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Testing-Type-Manual-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Project-Healthcare%20System-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" />
  <img src="https://img.shields.io/badge/QA%20Engineer-Farhana%20Islam-ff69b4?style=flat-square" />
</p>

---

## 📘 Overview

This repository contains **Manual Test Cases** for a complete **Healthcare Application**, designed according to the **Software Requirement Specification (SRS)**.  
It includes test coverage for all functional and non-functional modules — ensuring system reliability, accuracy, and user experience.

> 🧾 Each test case follows a structured QA format with Preconditions, Test Steps, Expected Results, and Status.

---

## 🧩 System Modules

| Module | Description |
|:-------|:-------------|
| 🧑‍⚕️ **Doctor Management** | Manages doctor registration, availability, and consultation schedules. |
| 🧑‍🤝‍🧑 **Patient Management** | Handles patient profiles, appointments, and medical history. |
| 💊 **Prescription & Medicine Management** | Ensures prescription creation, dosage validation, and record sharing. |
| 💳 **Payment & Billing** | Supports online payments, invoice generation, and refund management. |
| 📅 **Appointment Scheduling** | Manages booking, rescheduling, and cancellation of appointments. |
| 📊 **Reports & Analytics** | Generates daily, weekly, and monthly reports on operations. |
| 🔔 **Notifications & Alerts** | Sends alerts for appointment reminders, payments, and doctor updates. |
| 🔐 **Authentication & Security** | Handles login, logout, session timeout, and role-based access. |

---

## 🧾 Included File

| File Name | Description |
|------------|--------------|
| `Healthcare Application.xlsx` | Full manual test cases for all modules in the healthcare system. |

---

## 💡 Sample Test Case Example

| Field | Details |
|-------|----------|
| **Test ID** | TC_APPT_002 |
| **Module** | Appointment |
| **Test Scenario** | Book appointment with valid details |
| **Precondition** | Patient account must be active |
| **Test Steps** | 1️⃣ Log in as patient<br>2️⃣ Choose doctor and date<br>3️⃣ Click "Book Appointment" |
| **Expected Result** | Appointment booked successfully and confirmation message displayed |
| **Actual Result** | Appointment confirmed |
| **Status** | ✅ Pass |

---

## 📊 Test Execution Summary

| Metric | Description | Example |
|---------|--------------|----------|
| ✅ **Total Test Cases** | Total designed and executed | 200 |
| 🟢 **Passed** | Successfully validated cases | 180 |
| 🔴 **Failed** | Defects found and logged | 15 |
| 🟡 **Blocked** | Pending due to environment issues | 5 |
| 📈 **Pass Rate** | `(Passed / Total) × 100` | 90% |

---

## 🔍 Testing Approach

### 🧠 1. Test Design
- Designed using **SRS and User Stories**.
- Includes **Functional, Negative, and Edge** cases.

### 🧪 2. Test Execution
- Environment: **Web & Mobile Application**
- Devices Tested: 💻 Windows, 📱 Android
- Browsers: 🧭 Chrome, 🦊 Firefox, 🪟 Edge

### 🐞 3. Defect Management
- Bugs tracked in **JIRA / Excel Tracker**.
- Each defect documented with:
  - 🧾 Steps to Reproduce  
  - 📸 Screenshot  
  - 🧭 Expected vs Actual  
  - ⚙️ Severity & Priority  

---

## 📈 Reporting & Analytics

| Report Type | Description |
|--------------|-------------|
| 📅 **Daily Appointments Report** | Shows total and completed consultations per day. |
| 💰 **Revenue Report** | Displays total earnings by doctor or department. |
| 🩺 **Active Patient Report** | Lists ongoing treatments or scheduled visits. |
| 📂 **Export Options** | All reports downloadable in **PDF** and **Excel** formats. |

---

## 🔔 Notifications & Alerts

| Alert Type | Trigger | Expected Behavior |
|-------------|----------|------------------|
| 🕒 Appointment Reminder | 24 hrs before appointment | Email/SMS reminder sent |
| 💳 Payment Confirmation | After successful transaction | Payment receipt notification sent |
| ⚕️ Doctor Availability | Doctor reschedules/cancels | Patient alerted automatically |

---

## ⚙️ QA Execution Steps

1. 📥 **Download** the `Healthcare Application.xlsx` test case file.  
2. 🧾 **Review** the “Expected Result” and “Test Data” columns.  
3. 🧪 **Execute** all high-priority test cases first.  
4. 🐞 **Log any defects** found in the execution sheet or bug tracker.  
5. 📊 **Update status** (Pass / Fail / Blocked) accordingly.  
6. 🧱 Maintain **traceability** from SRS to Test Case to Defect.

---

## 🧮 Traceability Matrix Example

| Requirement ID | Feature | Test Case ID | Status |
|----------------|----------|--------------|--------|
| REQ-001 | Doctor Login | TC_DOC_001 | ✅ Pass |
| REQ-007 | Appointment Booking | TC_APPT_003 | 🟢 Pass |
| REQ-012 | Payment Gateway | TC_PAY_004 | 🔴 Fail |
| REQ-020 | Prescription Email | TC_PRES_006 | ✅ Pass |

---

## 🧱 Best QA Practices

✅ Ensure **complete coverage** — every SRS requirement has at least one test case.  
✅ Use **consistent naming** for test cases and IDs.  
✅ Include **test data**, **expected output**, and **validation criteria**.  
✅ Perform **positive**, **negative**, and **boundary** tests.  
✅ Update the test sheet **after every sprint/release**.  

---

## 🚀 Future Enhancements

- 🤖 Convert manual test cases into **Selenium + Mocha automation scripts**.  
- ☁️ Integrate with **TestRail or Zephyr** for centralized test management.  
- 🧪 Extend to **API Testing** using Postman.  
- 📈 Generate **automated reports** in HTML and PDF format.  

---

## 👩‍💻 QA Team

| Role | Name |
|------|------|
| 🧪 **QA Lead** | Farhana Islam |
| 💼 **Test Engineer** | [Farhana] |
| 🗓️ **Last Updated** | October 2025 |
| 🧾 **Document Version** | v1.0 |

---

## 🌟 Project Tagline

> 🧠 *“Quality is not tested in, it’s built in — thorough testing ensures trust.”*

---

<p align="center">
  <img src="https://img.shields.io/badge/Manual_Testing-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Healthcare_App-Verified-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SRS_Based_Testing-✓-purple?style=for-the-badge" />
</p>
