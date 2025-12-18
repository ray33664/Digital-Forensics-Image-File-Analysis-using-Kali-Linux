# Digital-Forensics-Image-File-Analysis-using-Kali-Linux
Performed digital forensic analysis on image and file evidence using Kali Linux tools such as Autopsy and ExifTool. Extracted metadata, verified evidence integrity using cryptographic hashing, and documented findings following ethical forensic procedures.
1. Introduction

Digital forensics is a branch of cybersecurity that deals with the identification, preservation, analysis, and presentation of digital evidence. With the rapid increase in cybercrimes, digital images and files are often used as crucial evidence in investigations. This project focuses on analyzing digital image and file evidence using forensic tools available in Kali Linux, following proper forensic procedures.

2. Objective

The main objectives of this project are:

To perform digital forensic analysis on image and file evidence

To extract hidden metadata from image files

To verify evidence integrity using cryptographic hashing

To identify possible signs of tampering

To generate a structured forensic report

3. Scope of the Project

This project is limited to:

Image files (JPG, PNG)

Basic document files

Metadata extraction and integrity verification

The project does not involve real criminal cases or sensitive personal data and strictly follows ethical guidelines.

4. Tools & Technologies Used

Kali Linux – Forensic investigation platform

Autopsy – Digital forensic analysis tool

ExifTool – Metadata extraction

md5sum / sha1sum – Hash generation

Linux Terminal – Evidence handling

5. Methodology
Step 1: Evidence Collection

Sample image and file evidence were collected from publicly available or self-created sources and stored securely in an evidence directory.

Step 2: Evidence Preservation

Files were copied using Linux commands to avoid altering original data.

Step 3: Integrity Verification

Hash values (MD5 and SHA1) were generated before analysis to ensure the authenticity of the evidence.

Step 4: Metadata Analysis

ExifTool was used to extract metadata such as:

Date and time of creation

Camera/device information

GPS location (if available)

Editing software used

Step 5: Forensic Analysis

Autopsy was used to analyze file timelines, metadata inconsistencies, and potential anomalies.

Step 6: Documentation

All findings were documented with screenshots and hash values to maintain forensic accuracy.
