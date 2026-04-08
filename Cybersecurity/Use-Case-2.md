# Microsoft Purview for Finance Department 

## Overview 

This use case outlines the process for a company to implement Microsoft Purview Sensitivity Labels specifically for the finance department. The goal is to automatically label financial information and prevent the finance team from sending emails and documents containing this type of information outside the department or with AI solutions like M365 Copilot. 

## Detailed Use Case 

### Scenario: 
The finance department handles sensitive financial information, including personal data, financial records, and intellectual property, which must be protected from unauthorized access and data breaches. The company aims to implement Microsoft Purview Sensitivity Labels to classify and protect this information automatically. 

### Requirements: 

Sensitive Information Type (SIT): Create a custom SIT to classify a type of financial data. For example Croatian Bank account number, Nigerian BVN, and test the SIT using a sample test file.

Sensitivity Labels: Create a Sensitivity label to apply to emails and files if the SIT created earlier is found.  

DLP Policies: Prevent the finance team from using M365 Copilot to process information related to the SIT earlier created. 
