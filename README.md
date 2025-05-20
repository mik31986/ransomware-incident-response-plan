# Ransomware Incident Response Plan Based on NIST
<!-- hide -->

> By [@rosinni](https://github.com/rosinni) and [other contributors](https://github.com/breatheco-de/ransomware-incident-response-plan/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)

*These instructions are also [available in Spanish](https://github.com/breatheco-de/ransomware-incident-response-plan/blob/main/README.es.md)*
<!-- endhide -->

### Before you start...

> We need you! These exercises are created and maintained in collaboration with people like you. If you find any errors or typos, please contribute and/or report them.

<!-- endhide -->

## 🌱 How to Start This Project
This exercise focuses on developing a **Ransomware Incident Response Plan** using the NIST cybersecurity framework, based on the case study of a fictional company called **TechCo**. The areas of identification, protection, detection, response, and recovery will be explored in the context of a ransomware attack.

## 🔍 Case Example: TechCo Under Ransomware Attack

The fictional company **TechCo**, dedicated to providing cloud services and managing sensitive customer data, has fallen victim to a ransomware attack.

### Incident Description:
- **Origin of the Attack**: An employee at TechCo received a phishing email that appeared legitimate, containing a malicious attachment disguised as an invoice. The employee downloaded the file, allowing attackers to install ransomware on TechCo's internal network.

- **Propagation**: The ransomware quickly spread to several critical servers. The affected systems include:
  - The **file server**, where essential documents and data for daily operations are stored.
  - The **customer database**, which contains sensitive personal and financial information.
  - The internal **backup systems** that, unfortunately, were also located within the compromised network.

- **Impact of the Attack**: Files were encrypted, and the company received a message demanding payment of 50 Bitcoins (equivalent to over $1,000,000) for the decryption key. The attackers threatened to permanently delete all files if the ransom was not paid within 72 hours.

- **Additional Issues**:
  - The network lacked proper segmentation, allowing the ransomware to affect both production systems and backups.
  - There was no early alert protocol or real-time monitoring systems, so the ransomware's spread was not detected until employees began to notice a lack of access to files.
  - Efforts to restore systems from backups failed, as these were also encrypted by the ransomware.

### Company Request:
The management of TechCo seeks to develop a formal response plan to prevent similar incidents from occurring in the future and to mitigate the impact of future attacks.

## 📝 Instructions

For the report, consider the following items.

1. **Identification:** Identify the critical assets of **TechCo** that have been affected or could have been targeted in the attack. Consider the key systems for the company’s operations and assess the potential vulnerabilities that facilitated the attack.

2. **Protection:** Describe the preventive measures that **TechCo** should have implemented to protect itself from the attack. Evaluate which security policies and controls would have mitigated or prevented the spread of the ransomware.

3. **Detection:** Provide methods and tools that **TechCo** could have used to detect the ransomware attack in its early stages. Consider how an early warning protocol could have improved the detection of the incident.

4. **Response:** Develop a detailed plan to respond to the ransomware attack in **TechCo**. Define the steps the team should follow once the incident is detected. Assign clear roles and responsibilities to the response team and specify how they should communicate both internally and externally.

5. **Recovery:** Describe the steps **TechCo** should take to restore systems and data affected by the ransomware attack. Make sure to include business continuity plans during and after recovery.

6. **Continuous Improvement:** Propose a method to assess the effectiveness of the response plan after the incident. Consider how the lessons learned can be integrated into future improvements of the plan.

## 📦 How to submit this project?

Submit a report covering each of the areas mentioned, aligned with the five core functions of the NIST Cybersecurity Framework: Identification, Protection, Detection, Response, and Recovery.

<!-- hide -->

## Contributors

Thanks to these amazing people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Rosinni Rodriguez (rosinni)](https://github.com/rosinni) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr), contribution: (bug reports) 🐛

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!

This and other exercises are used to learn to code by students at 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) led by Alejandro Sánchez and many other contributors. Learn more about our Programming Courses to become a [Full Stack Developer](https://4geeksacademy.com/us/coding-bootcamps/full-stack-developer), or our [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/data-science-machine-learning-bootcamp). You can also dive into cybersecurity with our [Cybersecurity Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/cybersecurity-bootcamp).

<!-- endhide -->

