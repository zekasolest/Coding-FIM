# Coding-FIM
Hashing Algorithms + Basic coding File Integrity Monitor (FIM)

### Project Overview

This project demonstrates the implementation of a File Integrity Monitor (FIM) using basic coding techniques and hashing algorithms. The primary objective is to ensure the integrity of files by detecting any unauthorized changes or modifications. The project is designed to showcase the practical application of cryptographic hashing in monitoring and maintaining the integrity of critical files.

![Screenshot 2024-07-01 at 3 32 02 PM](https://github.com/zekasolest/Coding-FIM/assets/36097391/55934470-802e-4749-89d9-877d98f7f21c)



### Features

- **Hashing Algorithms:** Utilizes cryptographic hashing algorithms (such as SHA-256) to generate unique hash values for files.
- **Baseline Creation:** Establishes a baseline by generating and storing hash values of files at an initial state.
- **Integrity Check:** Regularly compares current hash values of files with the baseline to detect any changes.
- **Alerts:** Provides notifications or logs when discrepancies are found, indicating potential unauthorized modifications.
- **User Interaction:** Simple user interface for adding files to be monitored and for initiating integrity checks.
- **PowerShell Implementation:** Written in PowerShell to leverage its scripting capabilities and ease of integration with Windows systems.

### Project Components

1. **Hash Calculation Function:** A function that takes a file path as input and returns its hash value using a specified hashing algorithm.
2. **Baseline Management:** Functions to create, update, and maintain a baseline of hash values for all monitored files.
3. **Integrity Verification:** A function that checks current file hash values against the baseline and reports any discrepancies.
4. **User Interface:** Simple prompts and outputs to guide the user through setting up and using the FIM.

### Use Cases

- **Security Monitoring:** Detect unauthorized changes to critical system files, configuration files, or application binaries.
- **Compliance:** Ensure compliance with security policies that require monitoring of file integrity.
- **Data Integrity:** Maintain the integrity of sensitive data by regularly verifying its unchanged state.

### Installation and Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/zekasolest/Coding-FIM.git
   cd Coding-FIM
   ```
2. **Run the Script:**
   Open PowerShell and run the main script to start the File Integrity Monitor.
   ```powershell
   .\Fim.ps1
   ```
3. **Follow Prompts:**
   Follow the on-screen prompts to add files to the monitoring list, create a baseline, and perform integrity checks.

Tutorial Credit

This project was created as part of a tutorial. Special thanks to the original author for their guidance:

https://www.youtube.com/watch?v=WJODYmk4ys8


This completes the illustration of coding up a simple File Integrity Monitoring with hashing algorithms. By following this guide, you can ensure the integrity of your critical files and detect any unauthorized changes efficiently.


Thank you for reading!

---
