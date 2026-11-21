# Networkwalks Cybersecurity Internship B084

## Project: PDF Password Auditing, Password Extraction and Hash Analysis

This repository documents practical work completed during the **Networkwalks Cybersecurity Internship (B084)**. The project focused on examining password-protected PDF files, performing controlled password-auditing exercises with John the Ripper (JTR), and extracting and calculating PDF hash values.

> **Responsible-use notice:** All activities were performed for authorized learning and assessment in the internship environment. Use these techniques only on files you own or have explicit permission to assess. Do not publish passwords, extracted hash strings, access tokens, or challenge flags.

## Project Modules

### PM1 — JTR and Password Extraction

**Objective:** Assess the password protection applied to three supplied PDF files and practise an authorized password-auditing workflow using John the Ripper (JTR).

**Activities**
- Worked with three password-protected PDF files supplied for the exercise.
- Prepared the PDF password data for an authorized JTR assessment workflow.
- Used password-auditing techniques to evaluate candidate passwords.
- Reviewed the tool's progress and result output.
- Validated successful password extraction by opening the corresponding protected PDF files.

**Outcome:** The screenshots document the JTR assessment process and successful password extraction/validation for the supplied exercise files. Password values are intentionally omitted from this repository.

### PM2 — Hash Calculator and PDF Hash Extraction

**Objective:** Calculate file hashes and extract hash values from PDF documents as part of password-auditing and file-analysis practice.

**Activities**
- Opened the Hash Calculator interface.
- Selected or uploaded a PDF for analysis.
- Generated a hash value for the selected file.
- Used a PDF hash extraction workflow to obtain the hash representation required for the assessment.
- Reviewed the resulting hash output.

**Outcome:** The screenshots show the Hash Calculator interface and PDF hash extraction output. Actual hash strings are intentionally redacted.

## Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| John the Ripper (JTR) | Authorized password auditing and candidate-password assessment |
| Hash Calculator | Calculating file hash values |
| PDF hash extraction utility | Extracting hash data from password-protected PDF files |
| PDF reader | Validating access to the supplied PDF documents |
| Windows environment | Running the desktop assessment utilities |
| Web browser | Accessing the hash calculator / extraction interface |

*Tool versions and exact command-line options were not visible in the supplied screenshots and are therefore not specified.*

## Workflow Summary

1. **Prepare the test files:** Identify the three supplied password-protected PDF documents.
2. **Perform the PM1 assessment:** Prepare the required PDF password data and conduct the authorized JTR password-auditing exercise.
3. **Review and validate:** Examine the assessment output and verify the extracted passwords against the relevant PDF files.
4. **Perform the PM2 analysis:** Calculate file hashes and extract PDF hash values using the available utilities.
5. **Document evidence:** Capture the tool interfaces and outcomes, while redacting passwords, hashes and challenge flags before publication.

## Evidence and Screenshots

The screenshots below are selected from the 14-page evidence document supplied for this project. Sensitive output has been blurred before inclusion.

### PM2 — Hash Calculator
![Hash Calculator interface](assets/screenshots/pm2-hash-calculator-redacted.png)

### PM1 — JTR assessment progress
![JTR assessment progress](assets/screenshots/pm1-jtr-audit-progress-redacted.png)

### PM1 — Password validation workflow
![Password validation workflow](assets/screenshots/pm1-password-validation-redacted.png)

### PM2 — PDF hash extraction
![PDF hash extraction interface](assets/screenshots/pm2-pdf-hash-extraction-redacted.png)

## Key Learning Outcomes

- Gained practical exposure to PDF password protection and authorized password auditing.
- Practised preparing PDF password data for a JTR assessment workflow.
- Understood the role of candidate-password evaluation in password management and security testing.
- Practised calculating file hashes and extracting PDF hash values.
- Learned to validate results and document technical evidence responsibly.
- Recognized the importance of protecting credentials and sensitive assessment output when publishing project work.

## Project Scope and Limitations

This documentation is based on the screenshots supplied for the internship project. The screenshots support the activities and outcomes described above, but do not establish exact software versions, command syntax, hash algorithms, runtime performance, or a full technical configuration. Those details have not been assumed.

## Repository Structure

```text
networkwalks-b084/
├── README.md
├── Project-Report.docx
└── assets/
    └── screenshots/
        ├── pm1-jtr-audit-progress-redacted.png
        ├── pm1-password-validation-redacted.png
        ├── pm2-hash-calculator-redacted.png
        └── pm2-pdf-hash-extraction-redacted.png
```

## Author

**Taiwo Peter Olatunji**  
Networkwalks Cybersecurity Internship — B084

---

*This project is presented for educational and professional portfolio purposes. All testing must remain within an authorized scope.*
