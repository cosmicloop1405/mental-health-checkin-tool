# 📄 User Stories – MindScope

This document outlines user stories for the MindScope mental health check-in tool. Each story is written from the perspective of different user roles and includes clear acceptance criteria to define when the story is considered complete.

---

## 👤 User Role: Employee

---

### ✅ US1 – Sign up and onboard  
**As an employee**, I want to sign up and set my check-in preferences so that I can start tracking my mental health.

**Acceptance Criteria:**  
- User can create an account with email and password  
- User is prompted to choose check-in frequency (daily, weekly, or monthly)  
- Preferences are saved in the user’s profile  

---

### ✅ US2 – Submit a check-in  
**As an employee**, I want to complete a quick check-in to record my mood and stress levels.

**Acceptance Criteria:**  
- User can rate their mood on a 1–10 scale  
- User can select stress level (e.g., Low, Moderate, High)  
- User can optionally add a note  
- Data is saved securely and timestamped  

---

### ✅ US3 – View personal dashboard  
**As an employee**, I want to view my mood and stress trends over time so I can reflect on patterns.

**Acceptance Criteria:**  
- Dashboard displays mood/stress charts by week and month  
- User can view individual check-in entries  
- Graph updates in real time when new data is entered  

---

### ✅ US4 – Set reminders  
**As an employee**, I want to receive reminders to complete my check-ins based on the frequency I selected.

**Acceptance Criteria:**  
- Reminders are sent via email or in-app notifications  
- Frequency matches the user’s selected preference  
- Reminders stop after user submits a check-in  

---

### ✅ US5 – Update profile and preferences  
**As an employee**, I want to change my check-in frequency or profile details at any time.

**Acceptance Criteria:**  
- User can access a profile settings page  
- Frequency and personal details are editable  
- Updates are reflected immediately  

---

### ✅ US6 – View monthly summaries  
**As an employee**, I want to receive a monthly summary of my check-ins so I can review my overall mental wellbeing.

**Acceptance Criteria:**  
- Monthly report includes average mood, stress level, and notable patterns  
- Report is available as a visual dashboard and/or downloadable format  
- Summary respects data privacy and includes only the user’s own data  

---

## 👨‍💼 User Role: Admin / HR

---

### ✅ US7 – View aggregate trends  
**As an HR admin**, I want to view anonymized team-level mental health trends to understand overall employee wellbeing.

**Acceptance Criteria:**  
- Admin dashboard shows group mood/stress trends  
- No personally identifiable information is shown  
- Admin can filter by time range and team (if available)

---

### ✅ US8 – Export reports  
**As an HR admin**, I want to download reports of team-level check-in trends to share with leadership.

**Acceptance Criteria:**  
- Reports are available in CSV or PDF format  
- Data is aggregated and anonymized  
- Export includes charts and average mood/stress scores  

---

### ✅ US9 – Ensure data privacy  
**As an HR admin**, I want to ensure no access to individual check-in entries so employees feel safe sharing honestly.

**Acceptance Criteria:**  
- Admin cannot see individual user data  
- Only aggregated, anonymized results are visible  
- Users are informed about privacy during onboarding  

---

### ✅ US10 – Employee deletion and data control  
**As an employee**, I want to delete my account and all related data at any time.

**Acceptance Criteria:**  
- Delete account option is available in settings  
- All associated data is deleted or flagged for deletion  
- User receives confirmation that their data has been removed

---

> ⚠️ *This document may evolve as the product scope changes or new features are added. Version control is maintained via GitHub commits.*
