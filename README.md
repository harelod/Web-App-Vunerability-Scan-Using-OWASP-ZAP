# Web-App-Vunerability-Scan-Using-OWASP-ZAP-Docummentation
This documentation focus on how OWASP ZAP can be used to scan a web application to identify vulnerablity and related remediation that can be applied.

## 1. Objectives of Lab
### i. To scan sample web application to identify vulnerabilities.
### ii. To explore related remedies.


## 2. Lab Set up Environment
- Vitual Machine: Oracle Virtual Box
- Operating System: Ethical-Hack- Kali Linux(Netacad)
- Tools: Zap/ OWASP ZAP
- Website Application: http://172.17.0.2/dvwa.vm
- Lab Guide: Parocyber ethical hacking training


# Selected Web Application Vulnerability Scan Results & Docummentations
OWASP Zap is a web application security scanner used to identify weaknesses in a website.

## 1. Initiating OWASP ZAP
### 1st Instruction: Search Zap from Kali Application list and Single click to open
<img width="803" height="917" alt="image" src="https://github.com/user-attachments/assets/4fb44562-9ebd-44fe-a149-5281df756bdb" />
<img width="522" height="564" alt="image" src="https://github.com/user-attachments/assets/3bb06e4f-ef5b-45b7-9e0d-7b2ae8b28429" />

### 2nd Instruction: Select first item on dialog box and click start
<img width="940" height="437" alt="image" src="https://github.com/user-attachments/assets/28d68030-2234-4134-913d-6ee3d28d0e6e" />
<img width="737" height="300" alt="image" src="https://github.com/user-attachments/assets/d2f844c8-64bd-417e-b466-40e013a378d2" />
NB: Close Add on dialog box

### 3rd Instruction: Select Automated Scan , Input ``` http://172.17.0.2/dvwa ``` at URL to attack and click Attack to start scanning
<img width="1913" height="889" alt="image" src="https://github.com/user-attachments/assets/23b1d522-7329-4e36-962b-8c9d6d5025b4" />

## 2. Results After Scan
<img width="940" height="440" alt="image" src="https://github.com/user-attachments/assets/1fb3b56e-dfb5-4e41-8071-139293314d1e" />

## 3. Findings, Risk and Count
This table shows the number of alerts of each alert type, together with the alert type's risk level. The percentages in brackets represent each count as a percentage, rounded to one decimal place, of the total number of alerts included in this report.

<img width="867" height="677" alt="image" src="https://github.com/user-attachments/assets/259c67bf-f113-4a37-9f55-f767b3b71b64" />
<img width="894" height="487" alt="image" src="https://github.com/user-attachments/assets/d2541464-2515-4620-a5a2-122936cb5438" />

## 4. Alerts Description and Remediation

### (a) Remote Code Execution - CVE-2012-1823
<img width="1281" height="743" alt="image" src="https://github.com/user-attachments/assets/97a18405-492c-4a74-b369-6ccd9b678e08" />

### (b) Source Code Disclosure - CVE-2012-1823
<img width="1285" height="793" alt="image" src="https://github.com/user-attachments/assets/c250881f-655c-4c56-b877-278a8433d623" />

### (c) Absence of Anti-CSRF Tokens
<img width="1316" height="746" alt="image" src="https://github.com/user-attachments/assets/40a5e2ab-8a45-4825-81df-35b27f060b31" />
<img width="998" height="634" alt="image" src="https://github.com/user-attachments/assets/6fe360bd-54c6-4bb5-a88d-d9a15c6f54db" />

### (d) Content Security Policy (CSP) Header Not Set
<img width="1196" height="435" alt="image" src="https://github.com/user-attachments/assets/af875f07-c127-4ba6-9d1f-7364560f4e35" />
<img width="1279" height="791" alt="image" src="https://github.com/user-attachments/assets/e8fb984a-7a53-4b84-a27d-17d364ea2336" />
<img width="1281" height="750" alt="image" src="https://github.com/user-attachments/assets/4ace6491-5641-461b-9578-c62fc8f0d934" />
<img width="1281" height="847" alt="image" src="https://github.com/user-attachments/assets/7b20af6f-9bf0-403c-8014-904325010f24" />

### (e) Directory Browsing
<img width="1280" height="709" alt="image" src="https://github.com/user-attachments/assets/9f7bd1be-a175-4603-b2a7-ee9cc39196de" />

### (f) Hidden File Found
<img width="1297" height="759" alt="image" src="https://github.com/user-attachments/assets/8dec2bce-e653-4aa4-a42f-e798a47cbd3e" />

### (g) Missing Anti-clickjacking Header
<img width="1120" height="461" alt="image" src="https://github.com/user-attachments/assets/a99acaa7-373e-4c54-a49f-1d24e7f2aaa6" />
<img width="1283" height="731" alt="image" src="https://github.com/user-attachments/assets/fa901dca-abb6-4b67-b257-398042d49de2" />
<img width="1228" height="663" alt="image" src="https://github.com/user-attachments/assets/fc04b72b-05ba-4741-a28b-224d39b83aea" />
<img width="1300" height="728" alt="image" src="https://github.com/user-attachments/assets/b328c0f4-a88d-4712-9d61-fe7a00909493" />
<img width="1298" height="686" alt="image" src="https://github.com/user-attachments/assets/0617c0b3-e8f7-44be-a939-d78bf03f2f14" />

### (h) Cookie No HttpOnly Flag
<img width="1284" height="699" alt="image" src="https://github.com/user-attachments/assets/b9b91ce8-5f7f-4049-985c-ed9ed3bd1303" />

### (i) Cookie without SameSite Attribute
<img width="1008" height="416" alt="image" src="https://github.com/user-attachments/assets/a086428e-b28a-41c2-b9dc-434c7173b873" />
<img width="1328" height="704" alt="image" src="https://github.com/user-attachments/assets/b50fd610-4f01-4710-ab1d-13ed7c30d4d2" />
<img width="1263" height="702" alt="image" src="https://github.com/user-attachments/assets/757a0ff1-67cf-4d66-bc6e-9303db0ea8d6" />
<img width="1306" height="696" alt="image" src="https://github.com/user-attachments/assets/483ed3c7-670b-420e-a21a-a2d85536c859" />

### (j) Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s)
<img width="1328" height="770" alt="image" src="https://github.com/user-attachments/assets/918e533d-eff6-46a9-8e97-e9052f3b3ce3" />

### (k) Server Leaks Version Information via "Server" HTTP Response Header Field
<img width="1223" height="387" alt="image" src="https://github.com/user-attachments/assets/80149810-d26e-4c09-a33d-22e251722346" />
<img width="1327" height="820" alt="image" src="https://github.com/user-attachments/assets/3d3ca13b-60a3-4a34-b813-0aac1a594422" />
<img width="1297" height="782" alt="image" src="https://github.com/user-attachments/assets/f02fccfd-ff61-4141-80b9-eed09990f67f" />

### (l) X-Content-Type-Options Header Missing
<img width="1293" height="808" alt="image" src="https://github.com/user-attachments/assets/5fd19976-7417-4f69-b590-8684c7cf0ef0" />

### (m) Authentication Request Identified
<img width="1300" height="687" alt="image" src="https://github.com/user-attachments/assets/6400c276-2fe8-4cd0-b269-fa9109c88d99" />

### (n) Session Management Response Identified
<img width="1277" height="703" alt="image" src="https://github.com/user-attachments/assets/bbfabc9b-3e68-4f5a-bb17-1792c980e03b" />

### (o) User Agent Fuzzer
<img width="1281" height="608" alt="image" src="https://github.com/user-attachments/assets/2ac1cd1c-9e97-4681-80ef-8fc31bce9893" />


## Conclusion of Docummentation
In summary, this project walks through using OWASP ZAP for automated security testing against a sample web application. It documents a practical scanning workflow from spidering and active scanning to reviewing results and provides a detailed analysis of discovered vulnerabilities. For each finding, the report breaks down the root cause and outlines actionable mitigation steps. 
The goal is to offer a clear, repeatable method for identifying common web security flaws and understanding how to address them effectively.


