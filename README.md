
# Cybersecurity Footprinting and Information Gathering

## 1. Project Description

Cybersecurity Footprinting and Information Gathering is a practical project focused on understanding how publicly available information about a website or domain can be collected using cybersecurity tools in Kali Linux. The project demonstrates basic reconnaissance techniques used to identify domain registration details, website technologies, and DNS information.

## 2. Objectives

- Understand the concept of cybersecurity footprinting.
- Learn basic information-gathering techniques.
- Identify domain registration information.
- Discover website technologies and server details.
- Understand DNS lookup and IP address resolution.
- Gain practical experience using Kali Linux tools.
- Understand ethical hacking and responsible information gathering.

## 3. Environment and Requirements

| Component | Details |
|---|---|
| Operating System | Kali Linux |
| Platform | Linux Terminal |
| Category | Cybersecurity |
| Project Type | Practical |
| Tools | WHOIS, WhatWeb, NSLOOKUP |

## 4. Tools and Commands

### 4.1 WHOIS

**Introduction:** WHOIS is a domain information lookup tool used to retrieve publicly available domain registration details.

**Purpose:**
- Identify domain registration information.
- Find registrar details.
- Check domain creation, update, and expiry dates.
- Identify name servers and domain status.

**Installation command:**

```bash
sudo apt update
sudo apt install whois
```

**Lookup command:**

```bash
whois example.com
```

**Expected information:** Domain Name, Registrar, Creation Date, Updated Date, Registry Expiry Date, Name Servers, and Domain Status.

**Result:** WHOIS helps users understand publicly available domain registration information.

### 4.2 WhatWeb

**Introduction:** WhatWeb is a website fingerprinting tool used to identify technologies and software used by websites.

**Purpose:**
- Identify web server technologies.
- Detect content management systems when detectable.
- Identify JavaScript frameworks and website technologies.
- Review publicly observable HTTP information.

**Installation command:**

```bash
sudo apt update
sudo apt install whatweb
```

**Lookup command:**

```bash
whatweb https://example.com
```

**Expected information:** HTTP Server, Website Title, HTML information, JavaScript Libraries, CMS Information (if detected), and Website Technologies.

**Result:** WhatWeb helps identify technologies used by a website through publicly observable responses.

### 4.3 NSLOOKUP

**Introduction:** NSLOOKUP is a DNS lookup utility used to query Domain Name System records.

**Purpose:**
- Find the IP address associated with a domain.
- Identify DNS servers.
- Check domain name resolution.
- Retrieve DNS information.

**Installation command:**

```bash
sudo apt update
sudo apt install dnsutils
```

**Lookup command:**

```bash
nslookup example.com
```

**Expected information:** DNS Server, Server Address, Domain Name, IP Address, and DNS Resolution Details.

**Result:** NSLOOKUP helps users understand how domain names are resolved into IP addresses.

## 5. Project Folder Structure

```text
Cybersecurity-Footprinting/
|
|-- README.md
|-- Report/
|   |-- Practical-Report.pdf
|   `-- Practical-Report.docx
|-- Screenshots/
|   |-- WHOIS/
|   |   `-- whois-screenshot.png
|   |-- WhatWeb/
|   |   `-- whatweb-screenshot.png
|   `-- NSLOOKUP/
|       `-- nslookup-screenshot.png
`-- Documentation/
    `-- Commands.txt
```

## 6. Practical Workflow

1. Start the Kali Linux operating system.
2. Open the terminal.
3. Install the required tools.
4. Select a domain that you are authorized to test.
5. Run the WHOIS command and examine domain registration information.
6. Run the WhatWeb command and examine detected website technologies.
7. Run the NSLOOKUP command and examine DNS information.
8. Save actual command output and screenshots.
9. Prepare the practical report.
10. Upload the report and screenshots to GitHub.

## 7. Practical Screenshots

The Screenshots folder should contain separate screenshots for each tool:

- **WHOIS:** Domain registration lookup.
- **WhatWeb:** Website technology detection.
- **NSLOOKUP:** DNS lookup and IP resolution.

Screenshots should represent actual tool executions. Illustrative screenshots must be clearly identified as demo samples.

## 8. Learning Outcomes

- Basic cybersecurity footprinting.
- Domain registration information gathering.
- Website technology identification.
- DNS lookup techniques.
- IP address resolution.
- Kali Linux terminal operations.
- Basic cybersecurity reconnaissance.
- Ethical hacking practices.

## 9. Ethical Considerations

- Perform practical activities only on authorized domains and systems.
- Do not attempt unauthorized access.
- Use publicly available information responsibly.
- Do not misuse collected information.
- Follow applicable cybersecurity laws and guidelines.

## 10. Conclusion

This project provides practical knowledge of cybersecurity footprinting and information gathering using Kali Linux. By using WHOIS, WhatWeb, and NSLOOKUP, users can understand domain registration information, website technologies, and DNS records. The project helps beginners develop fundamental cybersecurity skills and gain experience with commonly used reconnaissance tools.

## 11. Project Information

- **Project Title:** Cybersecurity Footprinting and Information Gathering
- **Operating System:** Kali Linux
- **Tools Used:** WHOIS, WhatWeb, NSLOOKUP
- **Project Category:** Cybersecurity
- **Project Purpose:** Educational and Practical Learning

## 12. Acknowledgement

This project was completed as part of cybersecurity practical learning. It helped develop basic knowledge of information gathering, website footprinting, and Linux-based cybersecurity tools.
