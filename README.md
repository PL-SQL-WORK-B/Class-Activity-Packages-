# Class-Activity-Packages-

# Group Members : - Alvin Munyambo 27146, - Jimmy Nsanza Iyarwema 27118, - Bonheur Rudasingwa 27367

# What the Question Was About

The task required creating a PL/SQL package for a Hospital Management System.
The system had to manage patients and doctors, support bulk insertion, return patient information, and update admission status.
The goal was to show skills in packages, functions, procedures, cursors, and bulk processing (FORALL).

# How we Solved It (Short Summary)

Created the required tables:

patients (ID, name, age, gender, admitted)

doctors (ID, name, specialty)

Defined a package specification containing:

A collection type for bulk patient data

bulk_load_patients (procedure for inserting multiple patients using FORALL)

show_all_patients (function returning a REF CURSOR)

count_admitted (function counting admitted patients)

admit_patient (procedure updating admitted status)

Implemented the package body:

Used BULK COLLECT + FORALL to efficiently insert many patients

Used SQL cursor return for listing all patients

Updated admission status and committed changes

Created test scripts to:

Load several patients at once

Display all patients

Admit a patient and verify the new admitted count

Overall, 
the package provides efficient patient management, supports bulk operations, and gives clear results through functions and procedures.

# END

Alvin Comment: Implemented the main package logic, including bulk processing and patient management functions.

Jimmy Comment: Assisted in testing all procedures/functions and verified bulk insertion, admission updates, and outputs.

Bonheur Comment:Helped in creating the GitHub organization, preparing documentation, and organizing all project files.




                   
