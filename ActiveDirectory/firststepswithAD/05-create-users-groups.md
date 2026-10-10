# 05 — Create Users and Security Groups

## Goal
Populate the departmental OUs with users and create security groups to manage permissions.

## Why This Step Matters
Users are the employees. Groups are how we assign permissions efficiently (e.g., instead of giving 50 people access to a folder one by one, we give the `HR-Team` group access). This follows the principle of Role-Based Access Control (RBAC).

## Steps Taken
1. Created users in their respective OUs:
   - HR: `Yugerten Ath Tamazgha` (Logon: `Yugerten.Tamazgha`)
   - Sales: `Yugerten Sales` (Logon: `sales.user`)
   - Dev: `Dev User` (Logon: `dev.user`)
   - IT: `IT User` (Logon: `it.user`)
2. Configured password settings: `P@ssw0rd2025!`, checked "Password never expires", unchecked "User must change password at next logon".
3. Created Global Security Groups inside each OU:
   - `HR-Team`, `Sales-Team`, `Dev-Team`, `IT-Team`
4. Added each user to their respective departmental group via the "Member Of" tab.

## Screenshots

![User Creation Menu](screenshots/05-01-user-menu.jpg)
![User Details](screenshots/05-02-user-details.jpg)
![User Password](screenshots/05-03-user-password.jpg)
![Users Created](screenshots/05-04-users-created.jpg)
![Add User to Group](screenshots/05-05-add-user-to-group.jpg)
![Group Members](screenshots/05-06-group-members.jpg)
![User Member Of](screenshots/05-07-user-memberof.jpg)
![Final OU Structure](screenshots/05-08-final-ou-structure.jpg)
