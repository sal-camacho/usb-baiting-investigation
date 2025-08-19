# Activity Overview 

In this activity, you will assess the attack vectors of a USB drive. You will consider a scenario of finding a USB drive in a parking lot from both the perspective of an attacker and a target.

USBs, or flash drives, are commonly used for storing and transporting data. However, some characteristics of these small, convenient devices can also introduce security risks. Threat actors frequently use USBs to deliver malicious software, damage other hardware, or even take control of devices. USB baiting is an attack in which a threat actor strategically leaves a malware USB stick for an employee to find and install to unknowingly infect a network. It relies on curious people to plug in an unfamiliar flash drive that they find.

## Scenario

You are part of the security team at Rhetorical Hospital and arrive to work one morning. On the ground of the parking lot, you find a USB stick with the hospital's logo printed on it. There’s no one else around who might have dropped it, so you decide to pick it up out of curiosity.

You bring the USB drive back to your office where the team has virtualization software installed on a workstation. Virtualization software can be used for this very purpose because it’s one of the only ways to safely investigate an unfamiliar USB stick. The  software works by running a simulated instance of the computer on the same workstation. This simulation isn’t connected to other files or networks, so the USB drive can’t affect other systems if it happens to be infected with malicious software.

---

## USB Attack Vector Investigation

This investigation documents a cybersecurity scenario involving a suspicious USB drive found in the parking lot of Rhetorical Hospital. It applies attacker mindset analysis and risk mitigation strategies to assess how personal and professional data stored on the device could be exploited. The activity emphasizes the importance of technical controls, employee awareness, and secure handling of removable media.

## My Contributions

- Identified sensitive contents including PII and internal HR documents  
- Applied attacker mindset to assess impersonation and phishing risks  
- Proposed layered controls: technical, operational, and managerial  
- Synthesized findings into a structured format aligned with AAA principles  

## USB Attack Vector Table

| **Category**         | **Details**                                                                                                                                                     |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Contents**         | - USB contained personal photos and HR files (e.g., new hire letter, shift schedule)  <br> - Included PII such as names, emails, and internal documents  <br> - Mixing personal and work files increases exposure risk |
| **Attacker Mindset** | - Files could be used to impersonate Jorge or target coworkers  <br> - Timesheets and HR data enable tailored phishing or social engineering  <br> - USB may have been staged to lure internal access |
| **Risk Analysis**    | - Malware like ransomware or remote access trojans could be hidden in .exe files  <br> - Plugging into a networked system could trigger compromise  <br> - Mitigations include disabling AutoPlay, enforcing MFA, RBAC, and employee training |

## Reflection

This activity reinforced the importance of treating unknown USB devices as potential threats. By analyzing attacker motivations and applying layered controls, I strengthened my understanding of physical attack vectors and internal security posture. The exercise also underscored how curiosity and careless handling of sensitive data can leave organizations vulnerable to significant security threats.

---

## Screenshot of Exercise Investigation & Contents of the USB Stick
![USB Attack Vector](images/image/usb-baiting-investigation.png)
> This image captures the full response submitted as part of the Google Cybersecurity Certificate Parking Lot USB activity.

<img width="632" height="816" alt="40" src="https://github.com/user-attachments/assets/be567192-330f-4368-aa2a-8ae135494600" />
<img width="638" height="551" alt="41" src="https://github.com/user-attachments/assets/2ad71da8-af60-4330-9560-4c0fc4a2dc2f" />
<img width="998" height="644" alt="42" src="https://github.com/user-attachments/assets/ca593559-0f7f-40a1-9f12-a8d281835691" />
