# Sign-Up-Flow-Analysis
This project analyzes the user signup and login flow, focusing on errors, drop-offs, and conversion rates. Using SQL for data extraction and Tableau for visualization, the analysis highlights bottlenecks in the authentication process and provides actionable insights for improving user experience.
-Data Sources
signup_conversion_rate.csv – Tracks signup attempts vs. successful registrations.
login_types_mod.csv – Contains login attempts and error messages.
signup_types_mod.csv – Captures different signup methods.
Queries written in SQL for preprocessing and aggregation.

-Tableau Story (signup_flow.twbx)
The .twbx file contains an interactive Story that walks through the entire analysis:
Signup Flow Funnel
Shows how many users start vs. complete signup.
Highlights major drop-off points.
Login Error Analysis
Bar chart of top login errors (Invalid email/password, popup_closed_by_user, Please fill in email!, etc.).
Quantifies frequency of errors → helps identify UX or backend issues.
Conversion Rate by Signup Type
Compares conversion success between different signup methods (email, social login, etc.).
User Retention & First Visit
Looks at whether successful signups return and log in again.

-Key Insights
Most common login failure = Invalid email or password (40k+ attempts).
A significant portion of failed signups comes from missing input fields (email/password).
Social logins vs. manual signups have different conversion efficiencies.
UX issues like popup closed by user suggest users abandoning mid-flow.

-How to Use

Download signup_flow.twbx
Open in Tableau Desktop or Tableau Public.
Navigate through the Story to explore signup and login patterns.

-Preview (Screenshots)
