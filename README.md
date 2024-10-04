# Microsoft-Windows-Defender-and-Firewall-for-Beginners

## Objective:-

The Microsoft-Windows-Defender-and-Firewall-for-Beginners is a guided project by coursera which guided me to build key skills such as being able to recognize common security threats, risks and learning how to set up cybersecurity defenses and updates like how to review and update threat definitions, run the Defender Antivirus quick scan, and configure Firewall Rules with and without Advanced Security. 

## Skills Learned:-

- Understanding the microsoft windows security virus and threat protection settings .
- Configuration of microsoft windows firewall rules with and without advanced security.
- Knowledge of reviewing and updating threat definitions.

# Description:-

## A. Microsoft Windows Defender Antivirus:-


### 1.Real-Time Protection:

![Screenshot 2024-09-27 204004](https://github.com/user-attachments/assets/577be86e-d07f-412e-b6bf-df61899333c4)

- Windows Defender Antivirus offers several types of scans to ensure comprehensive protection, which includes Quick Scan, Full Scan, Custom Scan, Offline Scan and Schedule Scan.
- Quick Scan: Allows the user to scan the areas of the system that are most likely to be targeted by malware. This scan is faster but less comprehensive. Here's what it typically involves:

- Memory Scan: Checks for active malware in your computer's memory.
- System Files: Scans all files and running programs on your hard disk. This scan is more thorough and can take several hours to complete, depending on the size of your drive and the number of 
  files.
- Registry Entries: Examines Windows Registry entries that are commonly used by malware to execute upon startup.
- Common Malware Locations: Scans common locations where malware is known to reside, such as the Windows directory and temporary files.
- Full Scan: This option thoroughly scans the entire system for threats.

- Custom Scan: This option allows the user to select specific files and folders to scan. This is useful if you suspect a particular area of your computer is infected.

- Offline Scan: This option allows users to scan the system before the operating system loads to detect and remove persistent threats.

- Scheduled Scan: This can be set up using the Task Scheduler to run regular scans at specified date and time to maintain system health.

---

### 2.Exclusions:

![Screenshot 2024-09-27 204855](https://github.com/user-attachments/assets/bf7ccc76-39bd-4321-931d-57a1162eb3c3)


- This option allows users to specify files, folders, and processes to be excluded from scans. After a scan is completed, Windows Defender Antivirus provides detailed results, which can be 
  accessed through the Windows Security Center. Actions based on scan results include:

- Quarantine: Isolating detected threats to prevent them from harming the system.
- Remove: Deleting detected threats from the system.
- Allow: Permitting certain detected items if they are known to be safe (adding to exclusions).

---

### 3.Tamper Protection:

![Screenshot 2024-09-27 204935](https://github.com/user-attachments/assets/efdd58ee-7c98-4909-bf01-92946b4252b0)


- Tamper Protection is a feature in Windows Security that helps prevent malicious apps from changing important security settings, including real-time protection and cloud-delivered protection.

---

### 4.Automatic Sample Submission:

![Screenshot 2024-09-27 205002](https://github.com/user-attachments/assets/fb636350-958f-4438-a54b-322b258d8ca2)


- Automatic Sample Submission is a feature in Windows Defender that helps protect your computer by automatically sending samples of suspicious files to Microsoft for analysis.

---

### 5.Regular Updates:

- This option allows users to automatically receive updated Windows Defender Antivirus and virus definitions regularly. To ensure optimal protection, Windows Defender relies on regular updates. - - These updates include the latest virus definitions, threat intelligence, and software improvements.

---


## B. Understanding Windows Firewall:-



### How Firewalls Work:- 

- A firewall works by monitoring all incoming and outgoing network traffic. The firewall decides whether to permit or deny the traffic based on a predefined set of rules.  Firewalls can monitor 
  and filter traffic using several different methods. 

- Packets are small pieces of data that travel across a network. A firewall that uses packet filtering reviews each packet that tries to access a network or device. Any packets that match known 
  threats or that have been explicitly denied are removed and all other packets are sent through to their destination. 

- Stateful inspection, also known as dynamic filtering, monitors the state of active network connections.  It relies on patterns to analyze and monitor traffic for potential threats. 

- A proxy firewall serves as a go-between for the requesting system and the internet. Information is first sent to the proxy service before it is forwarded to its destination. 

- Filters - Controlling Network Traffic

- Firewalls can be configured to meet the specific need of an individual or organization. The Inbound and outbound rules in Windows Firewall control the traffic allowed into and out of your 
  computer, respectively.

- Traffic can be approved or denied based on IP addresses, ports, domain names, and even specific words and phrases. These ensure that only authorized traffic is allowed 
  while unauthorized or potentially harmful traffic is blocked.

- Before you configure your firewall, it is important to create a plan. In many cases it’s best to deny all traffic except what is allowed. Rules that are too strict can limit important user 
  functionality.

- However, rules that are too loose can put your network at risk, so it’s usually easier to add approved access than it is to recover from a breach that happened because of loose 
  firewall rules. The more rules there are, the longer the firewall takes to review the traffic, so you’ll want to try to keep a lean, but efficient set of rules. 

- Inbound Rules :-
Inbound rules control the incoming network traffic to your computer. These rules help protect your system from unauthorized access and attacks by specifying which types of incoming connections are allowed or blocked.

- Outbound Rules :-
Outbound rules control the outgoing network traffic from your computer. These rules help manage what data leaves your computer and ensure that only authorized applications and services can send information.

- Network Profiles- The network profiles help tailor the firewall’s behavior based on the network’s trust level and security requirements.

- Domain Network: This is a network where the computer is connected to a domain of the company and is typically used in enterprise environments. This allows to apply settings for computers that are part of a corporate or organizational network, allowing for centralized management.

- Private Network: This is a network, such as a home or small office network, where the one or more computers can be trusted. Here, a more relaxed security settings can be applied, allowing devices within the same network to communicate more freely.

- Public Network: This is a network where the computer is connected in a public place, like a café or airport. This needs a restrictive settings to prevent unauthorized access and ensure maximum security in untrusted environments.

### Functions of Firewalls

- Threat Mitigation: Firewalls help prevent unauthorized access and cyber-attacks by blocking malicious traffic.

- Traffic Control: They regulate network traffic, allowing only legitimate communication.

- Enhanced Security: By setting rules, firewalls protect sensitive data and ensure compliance with security

---

# Steps:-

## Step 1: Locate Microsoft Windows Security Virus and Threat Protection

![Screenshot 2024-09-27 202942](https://github.com/user-attachments/assets/5cd2d8ae-dbab-4fa8-ab20-52588d8649b9)


## Step 2: Locate Microsoft Windows Security Virus and Threat Protection

![Screenshot 2024-09-27 203053](https://github.com/user-attachments/assets/cca88ae8-8d49-4cee-92ea-351770e1078e)


## Step 3: Update Threat Definitions

![Screenshot 2024-09-27 203156](https://github.com/user-attachments/assets/4f9a8a02-92cc-42ea-9765-76e1e03f9261)


## Step 4: Run Microsoft Windows Defender Antivirus Quick Scan 

![Screenshot 2024-09-27 203320](https://github.com/user-attachments/assets/382b4448-5bb0-4f80-a3b6-d2f848c77609)


## Step 5: Review Microsoft Windows Defender Antivirus Quick Scan Threat History 

![Screenshot 2024-09-27 203419](https://github.com/user-attachments/assets/24890b6c-0dd7-443a-9e33-a50300070d8b)


## Step 6: Configure Firewall Rules using Microsoft Windows Defender Firewall with and without Advanced Security

![Screenshot 2024-09-27 203653](https://github.com/user-attachments/assets/5bf93b42-f4be-4508-bb58-fa6693fad147)

---

## Certificate:-

   ![WhatsApp Image 2024-10-01 at 17 00 59_08540037](https://github.com/user-attachments/assets/0c59bcb6-6d80-4298-86c2-d46dc4ac773a)






