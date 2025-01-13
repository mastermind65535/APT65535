# APT65535
Advanced Persistent Threat 65535 PoC Spyware

# Disclaimer
> This software is intended ***exclusively for educational purposes and ethical cybersecurity research***. It is designed to help users understand potential vulnerabilities in systems so they can improve their security.
>
> By using this software, you agree to use it in compliance with all applicable laws and regulations. Unauthorized use, distribution, or deployment of this software against any system without the explicit permission of the system owner is strictly prohibited and may result in criminal and civil penalties.
>
> The creator(s) of this software assume no liability and are not responsible for any misuse or damages arising from the use of this software. Always obtain proper authorization before testing or analyzing systems using this software.

# Warning
> Be sure to read the license before using the project.

# Purposes
> This project is a **Proof of Concept (PoC) malware designed for showcase purposes only**. It was developed for Red Team purposes to measure the attack surface and evaluate how much information could be leaked after a security breach. The goal is to demonstrate potential scenarios that could occur if a system were compromised, highlighting the importance of effective security measures and incident response strategies.

# Features
## Privilege Escalation
| Level                      | Technique Description From External                                                                                                     | Privilege                  | Targets                                 |
|----------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|:---------------------------|:----------------------------------------|
| Level 1                    | [Unquoted Service Paths](https://www.ired.team/offensive-security/privilege-escalation/unquoted-service-paths)                          | SYSTEM                     |                                Services |
| Level 3                    | [DLL Proxying](https://www.ired.team/offensive-security/persistence/dll-proxying-for-persistence)                                       | Administrator              |                               Processes |
| Level 4                    | [DLL Hijacking](https://www.ired.team/offensive-security/privilege-escalation/t1038-dll-hijacking)                                      | Administrator              |                               Processes |
| Level 5                    | [COM Hijacking](https://www.ired.team/offensive-security/privilege-escalation/t1038-dll-hijacking)                                      | Administrator              |                               Processes |
