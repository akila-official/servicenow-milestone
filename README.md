# ServiceNow Milestone: User Creation and Role Assignment

## Overview
This repository contains the documentation for the User Creation and Role Assignment task completed in ServiceNow.

## Completed Tasks
- Created Users in ServiceNow (e.g., HR Support / Users)
- Configured User Profiles and details
- Assigned required Roles and Groups
- Verified Scoping and Access Permissions
  ---

# Milestone-2: Tables Creation

## Overview
Created a custom table in ServiceNow as per the project requirements.

## Details
- **Navigation:** Application Navigator -> System Definition -> Tables
- **Table Label:** Institution Details
- **Table Name:** u_institution_details
- Created custom table and submitted the form successfully.
- ---

# Milestone-3: Creation of Access Control List - READ

## Overview
Configured Access Control List (ACL) with READ operation for record-level security on the custom table.

## Details
- **Navigation:** Application Navigator -> System Security -> Access Control (ACL)
- **Role Elevated:** Security_admin role
- **Type:** record
- **Operation:** read
- **Name:** u_institution_details
- **Active:** true
- **Advanced:** true
- **Required Role:** bb1 (custom role added in Requires role related list)
- **Condition:** Branch is EEE
  ---

# Milestone-4: Creation of Access Control List - CREATE

## Overview
Configured Access Control List (ACL) with CREATE operation to grant record creation permissions on the custom table.

## Details
- **Navigation:** Application Navigator -> System Security -> Access Control (ACL)
- **Role Elevated:** Security_admin role
- **Type:** record
- **Operation:** create
- **Name:** u_institution_details
- **Active:** true
- **Required Role:** bb1 (custom role added in Requires role related list)

---

# Milestone-5: Creation of Access Control List - WRITE

## Overview
Configured Access Control List (ACL) with WRITE operation to allow updating records in the custom table.

## Details
- **Navigation:** Application Navigator -> System Security -> Access Control (ACL)
- **Role Elevated:** Security_admin role
- **Type:** record
- **Operation:** write
- **Name:** u_institution_details
- **Active:** true
- **Required Role:** bb1 (custom role added in Requires role related list)

---

# Milestone-6: Creation of Access Control List - DELETE

## Overview
Configured Access Control List (ACL) with DELETE operation to manage deletion permissions for records in the custom table.

## Details
- **Navigation:** Application Navigator -> System Security -> Access Control (ACL)
- **Role Elevated:** Security_admin role
- **Type:** record
- **Operation:** delete
- **Name:** u_institution_details
- **Active:** true
- **Required Role:** bb1 (custom role added in Requires role related list)

---

# Milestone-7: Conclusion

## Summary
All project milestones have been successfully completed:
- Created and configured users and roles in ServiceNow.
- Built the custom table `u_institution_details`.
- Configured Access Control Lists (ACLs) for READ, CREATE, WRITE, and DELETE operations using security_admin role and custom roles.
- Verified access conditions and security rules across all operations.
---

