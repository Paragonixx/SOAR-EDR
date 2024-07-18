# SOAR EDR

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Designing a playbook workflow
- Drawing out how I want the playbook to work
- How to make a playbook (story) that integrates slack, email and response capabilities -How to build a custom detection & response rule using LimaCharlie
- How to generate events using a password recovery tool 
- Automation , where I started creating my playbook/story in tines 
- Advanced understanding of SOAR concepts and practical application.
- Proficiency in analyzing logs.
- Ability to generate and recognize events
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Windows virtual machine in the cloud (Vultr) as my agent
- LimaCharlie acting as my Endpoint Detection & Response EDR tool 
- Tines acting as my SOAR 
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps


Example below.

*The Logical diagram used to set up my work flow!
![Paragon SOAR-EDR Logical Diagram](https://github.com/user-attachments/assets/d556f038-40a1-4f2a-9624-67dcc436ef36)


* Vultr - The Windows VM in the Cloud!
<img width="1104" alt="Vultr- The windows VM in the cloud" src="https://github.com/user-attachments/assets/b811385d-e40d-4686-89f3-647ae0a9b299">

* Installing LimaCharlie on Windows VM
![Installing LimaCharlie on Windows VM](https://github.com/user-attachments/assets/ff912699-bdd6-479c-8434-173997e3f627)

*Downloading "LaZagne" - To start generating telemetry!
<img width="818" alt="The download of LaZagne" src="https://github.com/user-attachments/assets/2f8d0d97-d71c-407e-8196-d314aa4c294e">

* LimaCharlie Detecting the new event!
<img width="1675" alt="LimaCharlie Showing the new event (LaZagne)" src="https://github.com/user-attachments/assets/d46c950b-e90d-47a6-a983-bf1a4c46b808">

* Creating the detection rule for "LaZagne" in LimaCharlie!
<img width="898" alt="The Detection and Respond rule- LimaCharlie" src="https://github.com/user-attachments/assets/d6921811-ebcc-4dae-9701-fe3013c874ad">

* During this phase, I created a Slack and Tines account (not shown) and pushed those detections to Tines!
<img width="1149" alt="Screenshot 2024-07-18 at 11 18 38 AM" src="https://github.com/user-attachments/assets/1ee7290c-4b68-4d3f-9325-665877053c8f">
