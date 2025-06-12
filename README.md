**Project #5(A-T): Implementing Security Policies**

- This project involved creating a Group Policy Object (GPO) that requires regular users on the network to change their passwords every 60 days while rending the 4 previous passwords on their accounts unusable, have a minimum of 12 characters for their passwords, and fulfill complexity requirements for their passwords.
- Another GPO was created to enforce an Account Lockout Policy, which would disable a user's account for 30 minutes after 3 failed authentication attempts. This is a measure to prevent brute-force attacks.
- Role Based Access Control was implemented via a GPO that restricts regular users from gaining access to the enterprise server as well restricting access to Remote Desktop. 
- A fine-grained password policy was created which requires enterprise network admins to have more complex passwords for their accounts than regular users and requires enterprise network admins to change their passwords more often.
