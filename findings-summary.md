# Findings Summary

## Registry Artifacts
Registry analysis showed evidence of user activity through TypedURLs, RecentDocs, and UserAssist. These artifacts helped reconstruct websites visited, recently accessed files, and application/session activity.

## Browser Artifacts
Internet Explorer history artifacts showed browser activity and local file access. These artifacts helped establish a timeline of user interaction with web and local resources.

## File Signature Analysis
File signature analysis helped identify files whose extensions did not match their actual file type. This is useful in investigations because users may rename files to hide their true format.

## Data Carving
Data carving recovered files from areas that may not be visible through normal file system navigation, such as unallocated space, slack space, or system files. This demonstrated how deleted or embedded evidence may still be recoverable.

## Email Artifacts
Email and task artifacts showed suspicious activity related to checks and financial documents. These artifacts supported the final case conclusion.

## Search Results
Indexed search provided fast keyword searching across processed evidence. Live search supported deeper pattern-based searching for sensitive financial-data patterns.

## System Information
Prefetch artifacts helped identify programs executed on the system. SAM user artifacts helped identify local accounts and connect user activity to specific profiles.

## Overall Conclusion
The FTK investigation showed how multiple forensic artifact types can be correlated to support an evidence-based case conclusion. The strongest evidence came from combining browser artifacts, registry activity, email/task artifacts, file carving, and search results.
