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

### User Creation
<table>
  <tr>
    <td width="50%"><b>1. Creating a User in the HR OU</b><br><img src="screenshots/05-01-user-menu.jpg" alt="User Menu"></td>
    <td width="50%"><b>2. Filling in User Details</b><br><img src="screenshots/05-02-user-details.jpg" alt="User Details"></td>
  </tr>
  <tr>
    <td width="50%"><b>3. Setting the Password</b><br><img src="screenshots/05-03-user-password.jpg" alt="User Password"></td>
    <td width="50%"><b>4. All Users Created</b><br><img src="screenshots/05-04-Users-Created.jpg" alt="Users Created"></td>
  </tr>
</table>

### Group Creation & Membership
<table>
  <tr>
    <td width="50%"><b>5. Adding a User to a Group</b><br><img src="screenshots/05-05-add-user-to-group.jpg" alt="Add User to Group"></td>
    <td width="50%"><b>6. Verifying Group Members</b><br><img src="screenshots/05-06-group-members.jpg" alt="Group Members"></td>
  </tr>
  <tr>
    <td width="50%"><b>7. User's "Member Of" Tab</b><br><img src="screenshots/05-07-user-memberof.jpg" alt="User Member Of"></td>
    <td width="50%"><b>8. Final OU Structure</b><br><img src="screenshots/05-08-final-ou-structure.jpg" alt="Final OU Structure"></td>
  </tr>
</table>
