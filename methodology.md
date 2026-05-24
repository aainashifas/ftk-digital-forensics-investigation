# Methodology

## 1. Case Setup
A new forensic case was created in FTK. The forensic image was added as evidence and processed using a custom evidence-processing profile.

## 2. Evidence Processing
The evidence-processing profile included additional processing options such as:
- Video thumbnail creation
- Language identification
- System information generation
- Compound file expansion
- Browser artifact parsing
- Event log parsing
- Index generation

## 3. File System Review
The evidence image was reviewed in the Explore tab to identify partitions, file systems, user folders, deleted files, and relevant document artifacts.

## 4. Document and Metadata Review
Documents were reviewed through FTK file categories. Metadata such as author, last saved by, created time, and modified time was used to support user activity analysis.

## 5. Registry Analysis
The user registry hive was opened in Registry Viewer. Artifacts reviewed included:
- TypedURLs
- RecentDocs
- UserAssist

These artifacts helped reconstruct user activity and application usage.

## 6. File Signature Analysis
File signature analysis was used to identify files where the extension did not match the actual file header. This helped detect renamed or disguised files.

## 7. Data Carving
Data carving was performed to recover deleted, embedded, or partially lost files based on file signatures rather than normal file system records.

## 8. Keyword and Pattern Searching
FTK indexed search was used for keyword searching. Live search was used for pattern-based searches, including financial-data patterns.

## 9. Email and Internet Artifact Review
Email artifacts were reviewed to identify suspicious messages and task items. Internet Explorer history artifacts were reviewed to reconstruct web activity and file access.

## 10. System Information Review
System artifacts such as Prefetch and SAM Users were reviewed to determine executed programs and identify local user accounts.

## 11. Password Recovery and Decryption
PRTK was used in a controlled lab context to support password recovery and encrypted-file decryption. Sensitive recovered values are excluded from this repository.

## 12. Evidence Organization
Important findings were bookmarked in FTK to support repeatability and reporting.
