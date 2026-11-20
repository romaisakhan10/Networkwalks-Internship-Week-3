# Module 1: Password Cracking with John the Ripper (JTR)

## 1. Project Overview

This module focuses on practical password auditing using **John the Ripper (JTR)** and its graphical interface, **Johnny GUI**.

The objective was to understand how password-protected PDF files can be audited by extracting their password hashes and using JTR to recover the password in an authorized lab environment.

## 2. Learning Objectives

- Understand the basics of password hashing.
- Learn how password-protected PDF files store password-verification data.
- Install and configure John the Ripper.
- Explore the Johnny graphical interface.
- Extract PDF password hashes.
- Perform password auditing using JTR.
- Verify the recovered password by opening the protected PDF.

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| John the Ripper | Password auditing |
| Johnny GUI | Graphical interface for JTR |
| PDF Hash Extractor | Extracting PDF password hashes |
| Windows | Operating environment |

## 4. Practical Implementation

### Step 1: Install John the Ripper

Downloaded and prepared John the Ripper on the Windows system.

### Step 2: Configure Johnny GUI

Installed Johnny GUI and configured it to locate the `john.exe` executable from the JTR installation directory.

### Step 3: Extract the PDF Hash

Used the PDF Hash Extractor to extract the password hash from the supplied protected PDF.

The extracted hash was saved in a text file named `hash1.txt`.

### Step 4: Load the Hash into Johnny

Opened Johnny GUI and loaded the extracted hash file using the password-file option.

### Step 5: Perform Password Auditing

Started the password-auditing process using John the Ripper and observed the result.

### Step 6: Verify the Result

Used the recovered password to open the protected PDF and confirmed that the file opened successfully.

## 5. Results and Observations

The practical was completed successfully.

- PDF hash extraction was performed.
- The extracted hash was loaded into Johnny.
- The password-auditing process was performed.
- The recovered password was used to open the protected PDF successfully.

## 6. Evidence and Screenshots

The following screenshots document the practical work:

### 1. PDF Hash Extraction
`JTR_hash1.png`

### 2. Successful PDF Verification
`PDF_OPENED.PNG`

## 7. Key Learnings

Through this practical, I learned:

- How password hashes are extracted from protected PDF files.
- How John the Ripper is used for password auditing.
- How Johnny GUI simplifies the use of JTR.
- How password complexity affects password-auditing difficulty.
- Why strong and unique passwords are important for digital security.

## 8. Conclusion

This practical provided hands-on experience with John the Ripper and Johnny GUI. I learned the process of extracting PDF password hashes, loading them into a password-auditing tool, and verifying the results. It strengthened my understanding of password security, hash extraction, and ethical password auditing.

---

**Internship:** Networkwalks  
**Week:** 03  
**Project:** Password Cracking with JTR  
**Domain:** Cybersecurity and Ethical Hacking
