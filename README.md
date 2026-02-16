# oracle_pdb_ass_II_28385_david

## 1. Overview
This assignment focuses on practical management of Oracle Pluggable Databases (PDBs) using Oracle Multitenant Architecture.  
The objective was to create and manage PDBs, create users inside a PDB, delete a temporary PDB, and access Oracle Enterprise Manager (OEM).  
All tasks were performed individually and documented with screenshots.

---

## 2. Oracle Environment Used
- Oracle Database (Multitenant Architecture)
- Oracle SQL Developer
- Oracle Enterprise Manager (OEM)
- Operating System: Windows
- Connection Role: SYSDBA

---

## 3. Task 1: Create a New Pluggable Database and User
A new Pluggable Database named:

**PDB Name:** `da_pdb_28385`

was created successfully from the root container (CDB$ROOT).  
After opening the PDB, a user was created inside the PDB with the following name:

**Username:** `david_plsqlauca_28385`

The user was granted the required privileges to allow database connections and future practical work.

Screenshots provided:
- PDB creation command and success message
- PDB open state
- User creation inside the PDB

---

## 4. Task 2: Create and Delete a Temporary PDB
A temporary PDB named:

**Temporary PDB:** `da_to_delete_pdb_28385`

was created to demonstrate PDB management.  
After verification, the temporary PDB was deleted completely including its data files.  
A final check confirmed that the PDB no longer existed in the system.

Screenshots provided:
- Temporary PDB creation
- Temporary PDB deletion
- Confirmation that the PDB no longer exists

---

## 5. Task 3: Oracle Enterprise Manager (OEM)
Oracle Enterprise Manager (OEM) was configured and accessed through a web browser.  
The dashboard successfully displayed the Oracle environment and the created PDB.  
The logged-in username is clearly visible in the screenshot as required.

Screenshot provided:
- OEM dashboard with visible username and PDB information

---

## 6. Challenges Encountered
Some minor issues were encountered during the process, including connection configuration and service name selection.  
These challenges were resolved by verifying the correct service name, using SYSDBA role for administrative tasks, and ensuring the PDB was opened before creating users.

---

## 7. Repository Structure
The repository contains the following:
- `README.md` (this report)
- `screenshots/` folder with:
  - PDB creation screenshots
  - PDB deletion screenshots
  - OEM dashboard screenshot

---

## 8. Integrity Statement
I declare that this assignment was completed individually and reflects my own work.  
No commands, screenshots, or documentation were copied from other students.  
This work complies with the academic integrity guidelines provided in the assignment instructions.

---

## 9. Submission Information
- **Repository Link:** (paste your GitHub repository link here)
- **PDB Name Created:** da_pdb_28385
- **Issues Encountered:** Yes / No
