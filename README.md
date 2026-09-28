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
-

