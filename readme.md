# FINAL PROJECT


## Closed Issues
Below are the links to closed issues along with brief descriptions:

1. **[Issue #1 - Email Verification Failure](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/issues/1)**  
   When a new user is created, the system fails to send a verification email to Mailtrap. This issue has been resolved by ensuring the email service is correctly configured and triggers the verification process upon user creation.

2. **[Issue #2 - Admin Email Verification](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/issues/3)**  
   Previously, the system allowed admin accounts to bypass email verification, which is incorrect. This issue has been resolved by ensuring that admins are also required to verify their email before accessing the system.

3. **[Issue #3 - Weak Password Allowed](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/issues/5)**  
   The system allowed weak passwords like '12345678' to be approved, which is a security risk. This issue has been fixed by implementing a password strength validator that ensures passwords contain uppercase and lowercase letters, numbers, and special characters (e.g., $, #, etc.).

4. **[Issue #4 - Incorrect Role Update](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/issues/7)**  
   During email verification, the role was incorrectly updated to AUTHENTICATED even if the role was ADMIN. This issue has been fixed to ensure that only users with the role ANONYMOUS are updated to AUTHENTICATED after successful email verification.

5. **[Issue #5 - 401 Error on Token Handling](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/issues/9)**  
   The require_role dependency did not properly handle invalid or missing tokens, resulting in a 401 error when accessing the delete_user endpoint. This issue has been resolved by improving token validation to ensure proper handling of missing or invalid tokens.

---
## New Tests
You can explore the details here in the new_tests branch: 
 **[Link to Test branch](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/tree/new_tests)** 

---

## New Feature: User Search and Filtering
You can explore the details here in the feature branch:  
**[Link to the Feature Branch](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/tree/feature)**

---
### About feature
- The Search and Filtering feature allows administrators to easily find and manage users. Admins can search by username, email, or role and filter users based on account status or registration date range. The user management API now supports these capabilities for improved efficiency.

### Feature Image
![Image](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/blob/main/FinalProject1.png)
---

## Docker Hub Repository
### You can find the Docker image for this project on Docker Hub:  
### [Link to Docker Hub Repository](https://hub.docker.com/repository/docker/ykshah1309/final_project/general)
![Image](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-FinalProject-Spring2025-yks/blob/main/FinalProject2.png)
---

## My Experience

I had a very good experience throughout this course, guided by Professor Keith Williams. This course provided me with the opportunity to dive into various cutting-edge technologies and tools, such as Docker and GitHub Actions, which were entirely new to me. These tools have significantly expanded my technical skill set, enhancing my ability to deploy, manage, and automate workflows efficiently.

One of the most valuable aspects of this course was the exposure to industry-level coding practices. The assignments and projects challenged me to adopt professional software development standards, including version control using Git, continuous integration with GitHub Actions, and containerization with Docker. These experiences have not only deepened my understanding of modern software development but also equipped me with the tools needed to work on real-world projects.

The guidance provided by Professor Keith Williams was invaluable, and his expertise in the field ensured that the learning process was both enriching and insightful. Overall, this course has been an incredibly rewarding experience. I feel much more confident in applying my newfound skills to real-world projects, and I look forward to leveraging these skills in my future career.