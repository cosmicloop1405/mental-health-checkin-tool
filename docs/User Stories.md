# 📄 User Stories – MindScope

---

## Authentication & Access

### Sign up and onboard  
**As an employee**, I want to sign up and set my check-in preferences so that I can start tracking my mental health.

**Acceptance Criteria:**  
- User can create an account with email and password  
- User is prompted to choose check-in frequency (daily, weekly, or monthly)  
- Preferences are saved in the user’s profile  

---

### Log in to portal  
**As an employee**, I want to log in to the portal so I can access my dashboard and complete check-ins.

**Acceptance Criteria:**  
- User can enter email and password to log in  
- If the password is incorrect, an error message is displayed  
- If login is successful, user is redirected to the main dashboard  

---

### Forgot password  
**As an employee**, I want to reset my password if I forget it so that I can regain access to my account.

**Acceptance Criteria:**  
- User can click a "Forgot Password?" link on the login page  
- User receives a secure password reset email  
- User can set a new password and log in with it  
- A confirmation message is shown after successful reset  

---

### First-time login experience  
**As an employee**, I want to be guided through my first login so I know how to set up and use the tool.

**Acceptance Criteria:**  
- First-time users are guided through a brief onboarding (e.g., “Set your check-in frequency”)  
- The user is shown a welcome message and tips  
- After completing onboarding, the user is redirected to their dashboard  

---

### Logout  
**As an employee**, I want to log out of my account so I can keep my data secure when I'm not using the app.

**Acceptance Criteria:**  
- A “Logout” button is available on the dashboard or nav bar  
- Clicking it ends the user session and returns to the login page  
- No cached user data is left in the browser  

---

### Handle login errors  
**As an employee**, I want to be clearly informed when something goes wrong during login so I can take action.

**Acceptance Criteria:**  
- If email or password is incorrect, a clear error message appears (e.g., “Invalid credentials”)  
- If the account does not exist, user is prompted to sign up  
- If too many failed attempts occur, user sees a rate-limit or captcha prompt  

---

## Employee Portal

### Submit a check-in  
**As an employee**, I want to complete a quick check-in to record my mood and stress levels.

**Acceptance Criteria:**  
- User can rate their mood on a 1–10 scale  
- User can select stress level (e.g., Low, Moderate, High)  
- User can optionally add a note  
- Data is saved securely and timestamped  

---

### View personal dashboard  
**As an employee**, I want to view my mood and stress trends over time so I can reflect on patterns.

**Acceptance Criteria:**  
- Dashboard displays mood/stress charts by week and month  
- User can view individual check-in entries  
- Graph updates in real time when new data is entered  

---

### Set reminders  
**As an employee**, I want to receive reminders to complete my check-ins based on the frequency I selected.

**Acceptance Criteria:**  
- Reminders are sent via email or in-app notifications  
- Frequency matches the user’s selected preference  
- Reminders stop after user submits a check-in  

---

### Update profile and preferences  
**As an employee**, I want to change my check-in frequency or profile details at any time.

**Acceptance Criteria:**  
- User can access a profile settings page  
- Frequency and personal details are editable  
- Updates are reflected immediately  

---

### View monthly summaries  
**As an employee**, I want to receive a monthly summary of my check-ins so I can review my overall mental wellbeing.

**Acceptance Criteria:**  
- Monthly report includes average mood, stress level, and notable patterns  
- Report is available as a visual dashboard and/or downloadable format  
- Summary respects data privacy and includes only the user’s own data  

---

### Account deletion and data control  
**As an employee**, I want to delete my account and all related data at any time.

**Acceptance Criteria:**  
- Delete account option is available in settings  
- All associated data is deleted or flagged for deletion  
- User receives confirmation that their data has been removed  

---

## Admin / HR Portal

### View aggregate trends  
**As an HR admin**, I want to view anonymized team-level mental health trends to understand overall employee wellbeing.

**Acceptance Criteria:**  
- Admin dashboard shows group mood/stress trends  
- No personally identifiable information is shown  
- Admin can filter by time range and team (if available)

---

### Export reports  
**As an HR admin**, I want to download reports of team-level check-in trends to share with leadership.

**Acceptance Criteria:**  
- Reports are available in CSV or PDF format  
- Data is aggregated and anonymized  
- Export includes charts and average mood/stress scores  

---

### Ensure data privacy  
**As an HR admin**, I want to ensure no access to individual check-in entries so employees feel safe sharing honestly.

**Acceptance Criteria:**  
- Admin cannot see individual user data  
- Only aggregated, anonymized results are visible  
- Users are informed about privacy during onboarding  

---

*This document will be updated continuously as new features and stories are identified.*
