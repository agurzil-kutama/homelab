# 04 — Create Organizational Units (OUs)

## Goal
Create a logical structure for the FINAL.LOCAL domain by creating Organizational Units (OUs) for each department.

## Why This Step Matters
Instead of dumping all users and computers into the default "Users" container, we create OUs to represent the company structure. This allows us to apply specific Group Policy Objects (GPOs) to specific departments later (e.g., Sales might have different network drive access than HR).

## Steps Taken
1. Opened **Active Directory Users and Computers** via Server Manager Tools.
2. Expanded `FINAL.LOCAL`.
3. Right-clicked `FINAL.LOCAL` → New → Organizational Unit.
4. Created the parent OU: `FINAL-Company`.
5. Inside `FINAL-Company`, created four child OUs:
   - `HR`
   - `Sales`
   - `Dev`
   - `IT`

## Screenshots

![Open ADUC](screenshots/04-01-open-aduc.jpg)
![Create Parent OU](screenshots/04-02-create-parent-ou.jpg)
![Name Parent OU](screenshots/04-03-name-parent-ou.jpg)
![Create Child OUs](screenshots/04-04-create-child-ous.jpg)
![Name HR OU](screenshots/04-05-name-hr-ou.jpg)
![OUs Completed](screenshots/04-06-ous-completed.jpg)
