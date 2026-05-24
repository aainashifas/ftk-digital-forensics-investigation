# FTK Digital Forensics Investigation

## Overview
This project documents a digital forensic investigation completed using Forensic Toolkit (FTK), Registry Viewer, and Password Recovery Toolkit (PRTK). The investigation used a forensic disk image in a controlled academic lab environment to analyze user activity, recover artifacts, search for evidence, examine registry data, review email and internet history, and generate a forensic case report.

## Objective
The objective of this lab was to use FTK to examine a forensic image, identify relevant evidence, bookmark important artifacts, and produce findings that are repeatable and support a case conclusion.

## Scenario
A forensic image of a user workstation was provided for analysis. The investigation focused on identifying evidence of suspicious activity related to financial documents, checks, card-related searches, and encrypted files.

## Tools Used
- Forensic Toolkit (FTK)
- AccessData/Exterro Registry Viewer
- Password Recovery Toolkit (PRTK)
- Windows 11 forensic workstation
- EnCase evidence image format

## Skills Demonstrated
- Digital forensic case setup
- Evidence image processing
- File system and partition analysis
- Registry artifact analysis
- File signature analysis
- Data carving
- Indexed keyword searching
- Live pattern searching
- Email artifact review
- Internet history analysis
- Prefetch and SAM user analysis
- Bookmarking evidence
- Password recovery workflow
- Decryption workflow
- Forensic reporting

## Methodology
1. Created a new FTK case and added the forensic image.
2. Configured evidence processing options, including system information generation, language identification, thumbnails, and compound file expansion.
3. Reviewed partitions and file systems within the forensic image.
4. Analyzed documents, file metadata, and user-created artifacts.
5. Opened the user registry hive in Registry Viewer to examine TypedURLs, RecentDocs, and UserAssist.
6. Reviewed file signatures and identified extension mismatches.
7. Performed data carving to recover deleted or embedded files.
8. Used indexed search and live search to locate keywords and card-number patterns.
9. Reviewed email artifacts and suspicious task items.
10. Examined Internet Explorer history artifacts and system information artifacts.
11. Used PRTK to support encrypted file recovery and decryption.
12. Bookmarked evidence and summarized findings in a forensic case report.

## Key Findings
- Registry artifacts showed user activity through TypedURLs, RecentDocs, and UserAssist entries.
- Internet history artifacts showed browser activity related to financial theft research.
- Data carving recovered files that were not easily visible through normal file system browsing.
- Email/task artifacts suggested suspicious planning related to checks.
- Live search identified sensitive financial-data patterns in the evidence image.
- System information artifacts such as Prefetch and SAM Users helped connect activity to user accounts.

## What I Learned
This lab strengthened my understanding of how forensic investigations combine multiple artifact types to support a case conclusion. I practiced using FTK to process evidence, identify relevant files, recover deleted data, analyze registry and internet artifacts, and organize findings through bookmarks and reports.

## Disclaimer
This project was completed in a controlled academic lab environment using provided forensic training images. No real personal, confidential, or production data is included in this repository. Sensitive values, credentials, and raw evidence files are intentionally excluded.
