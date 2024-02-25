<h1>Project: ALU Registration System and Automation</h1>

Overview

This project encompasses two key components:

ALU Registration System: A shell script application (main.sh) that enables users to manage student registration data for the Bachelor of Software Engineering cohort.
Automation with Linux: Shell scripts (move-to-directory.sh and backup-Negpod_ID.sh) that automate file movement and directory backup for the registration system files.
Question 1: Shell Programming - ALU Registration System

Expected Files:

main.sh (shell script for student registration)
students-list_1023.txt (file to store student records)
select-emails.sh (shell script to extract student emails)
student-emails.txt (file to store extracted emails)
Functionality:

main.sh:
Creates student records with user-provided information (email, age, ID).
Saves each record to students-list_1023.txt.
Displays all saved students in the terminal.
Allows deletion and update of student records by ID.
Provides an exit option.
select-emails.sh:
Extracts student email addresses from students-list_1023.txt.
Saves the extracted emails to student-emails.txt.
Question 2: Automation with Linux

Expected Files:

move-to-directory.sh (shell script to move files to a directory)
negpod_id-q1 (directory to store registration system files)
backup-Negpod_ID.sh (shell script to back up the directory)
Functionality:

move-to-directory.sh:
Automatically moves the four files created in Question 1 to a directory named negpod_id-q1 (replace negpod_id with your actual Negpod ID).
backup-Negpod_ID.sh:
Backs up the negpod_id-q1 directory to a remote server using the provided credentials:
Host: 64293e56bc62.3a2627c1.alu-cod.online
Username: 64293e56bc62
Password: 328d3b338a4ced526c9a
Backup location: /summative/1023-2024j (replace 1023-2024j with your year and cohort)
Instructions

Set Up Files:
Create the shell scripts (main.sh, select-emails.sh, move-to-directory.sh, backup-Negpod_ID.sh) with the appropriate code.
Create the students-list_1023.txt and student-emails.txt files.
Run Scripts:
Execute main.sh to interact with the student registration system.
Run select-emails.sh to extract and save student emails.
Use move-to-directory.sh to move the files to the negpod_id-q1 directory.
Execute backup-Negpod_ID.sh to back up the directory to the remote server.
Test Backup:
Use a second sandbox to test if the backup script works successfully.
