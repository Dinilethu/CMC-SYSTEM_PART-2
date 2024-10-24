Contract Monthly Claim System (CMCS)
Overview
The Contract Monthly Claim System (CMCS) is a web application designed for Independent Contractor (IC) lecturers to submit their monthly claims for hours worked. 
It facilitates an efficient and transparent process for submitting, approving, and tracking claims.
The system allows programme coordinators and academic managers to verify and approve claims, ensuring proper documentation and approval workflows.
And to run and access the code you should open this particular file/folder "CMC SYSTEM_DINI".

Features
Lecturer Claim Submission: IC lecturers can submit claims for hours worked, including details like lecturer name, hours worked, and hourly rate.
Claim Approval: Programme coordinators and academic managers can view, approve, or reject submitted claims.
Claim Status Tracking: Track the status of each claim as it progresses through the approval stages.
Role-Based Access: Different user roles (lecturers, coordinators, academic managers) have access to specific functionality.
Responsive Design: The application is optimized for both desktop and mobile views.
Technologies Used
ASP.NET Core MVC: For building the web application.
C#: Backend logic and data processing.
Entity Framework Core: For database management and ORM.
SQL Server: Database for storing lecturer claims and approval statuses.
Razor View Engine: For dynamic page generation and rendering.
AJAX: For real-time updates and status changes without full-page reloads.
HTML/CSS: For frontend design.
Bootstrap: For responsive UI design.

User Roles
Lecturer:

Submit claims for hours worked.
View the status of submitted claims.
Programme Coordinator:

View submitted claims.
Approve or reject claims from lecturers.
Academic Manager:

Final approval for claims.
Can override coordinator decisions if necessary.
Pages Overview
Home: Introduction to the system and navigation.
About: Information about the CMCS system.
Contact: Support contact details.
SubmitClaim: Form for lecturers to submit monthly claims.
ApproveClaim: Interface for coordinators and managers to view and approve claims.

Future Improvements
Add email notifications for claim approvals and rejections.
Implement audit logging for all claim-related actions.
Enhance security with two-factor authentication (2FA).
Troubleshooting
Database Connection Errors: Ensure that the connection string in appsettings.json is correct and that the SQL Server is running.
Page Not Loading: Check the browser console for any JavaScript or network errors and ensure the server is running.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

Contact
For any inquiries or support, please contact us via email: assistance@cmcsystem.com.
