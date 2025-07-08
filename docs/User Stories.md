# User Stories – MindScope

---

### 🔐 Authentication & Access

1. **Employee sign up and onboard**  
   As an employee, I want to create an account and set my check-in preferences so that I can start tracking my mental health.  
   **Acceptance Criteria:**  
   - User can create an account with email and password  
   - User is prompted to choose check-in frequency (daily, weekly, monthly)  
   - Preferences are saved in the user’s profile  

2. **Employee log in to portal**  
   As an employee, I want to log in so I can access my dashboard and complete check-ins.  
   **Acceptance Criteria:**  
   - User can log in with email and password  
   - Incorrect password shows an error message  
   - Successful login redirects to the dashboard  

3. **HR/Admin log in to portal**  
   As an HR admin, I want to log in so I can access admin tools and reports.  
   **Acceptance Criteria:**  
   - HR admin can log in with secure credentials  
   - Successful login redirects to admin dashboard  

4. **Role-based access control**  
   As a user, I want the system to show features based on my role so I see only relevant data.  
   **Acceptance Criteria:**  
   - Different dashboards/views based on role (employee vs HR/admin)  
   - Unauthorized pages or actions are blocked  

5. **Forgot password**  
   As a user, I want to reset my password if I forget it so I can regain access.  
   **Acceptance Criteria:**  
   - Password reset link available via email  
   - Secure reset process with confirmation  

6. **Logout**  
   As a user, I want to log out to keep my data secure.  
   **Acceptance Criteria:**  
   - Logout ends session and returns to login page  

---

### 👤 Employee Portal

1. **Submit a check-in**  
   As an employee, I want to record my mood and stress levels quickly.  
   **Acceptance Criteria:**  
   - Mood rated on a scale  
   - Stress level selected  
   - Optional notes added  
   - Data saved with timestamp  

2. **View personal dashboard**  
   As an employee, I want to see trends over time.  
   **Acceptance Criteria:**  
   - Dashboard with mood/stress charts by week/month  
   - Past check-ins accessible  

3. **Set reminders**  
   As an employee, I want reminders based on my check-in frequency.  
   **Acceptance Criteria:**  
   - Email or in-app reminders sent  
   - Reminders stop after check-in  

4. **Update profile and preferences**  
   As an employee, I want to change my check-in frequency or profile info anytime.  
   **Acceptance Criteria:**  
   - Editable settings saved immediately  

---

### 🛠️ Admin / HR Portal

1. **View aggregate trends**  
   As an HR admin, I want anonymized team-level mental health trends.  
   **Acceptance Criteria:**  
   - Aggregate dashboard with no personal info  
   - Filters by date and team available  

2. **Export reports**  
   As an HR admin, I want to download reports for leadership.  
   **Acceptance Criteria:**  
   - Export in CSV or PDF format  
