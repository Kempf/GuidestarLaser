# Guide Star Laser Project

Repository created on: 04/08/2017

The goal of the project is to develop a **preliminary design** for mounting the EOS and ANU guide star lasers on the EOS 1.8m telescope at Mt. Stromlo, including a document detailing the full requirements and specifications with the highest level of precision available 
with the information avaiable for the most likely configurations, and CAD models supporting this information.

The telescope is used for **laser-tracking satellites** and **space debris**, but its accuracy is limited by the **atmospheric distortions**. A laser guide star (produced by a **guide star laser**, which excites the sodium layer in the atmosphere)
can be used to correct the atmospheric distortions using **adaptive optics** on the telescope. Two such guide star lasers (GSLs) are currently being made for the telescope.

The key components of the mounting are the **mechanical interface** (the support frame and actual physical mounting technique, including vibration limiting techniques), the **environmental
considerations** such as air quality and humidity limitations, the **electrical and communication** limitations involved with mounting the lasers and connecting them to the control system,
due to limitations in the available connections within the dome, and the **logistical concerns**, due to the difficulty of mounting a large laser into the dome, which is a confined space. 

The team works on this **weekly** on Fridays 9-5 in a shared space at AITC, Mt Stromlo, enabling strong communication within the team, as well as ease of communications with our client and stakeholders. 
Additional work is completed externally, including meetings for feedback reviews and individual work.

![project diagram](http://i.imgur.com/0ppTVj8.png)

(Diagram supplied by EOS)

## Team

| Member Name  	|   UID    | Responsibilities          | Skills                               	|
|--------------	|--------------------------	|--------------------------------------	|--------------------|
| Alex Dalton  	|  u5889439      | Project Manager           |Mechanical/Materials Eng, CAD, Project management
| Brian Ma  	|  u5893274     | Environmental req's.      |Power electronics/system Eng, MATLAB, Python, embeded C, microprocessor, wirless communication               |
| Chris Leow  	|  u5827718     | Minutes, Mechanical int. |Mechanical/Materials Eng, Fluid Mechanics & Heat Transfer, Project management, secretary experience, technical dawing|
| Paul Apelt  	|  u5568225      | Project requirements, CAD      |Electronic/Mechatronic, MATLAB, Python |
| Steve Lonergan|  u5349877     | Point of Contact, vibration|Electronic/Mechatronic, MATLAB, Project Management|
| Wenjie Mu  	|  u5354143     | Accessibility analysis |Mechatronics/Renewable Systems, MATLAB, Hardware Programming                                       |
*"Responsibilities" are the areas for which the team member is the key source of knowledge.
All team members will contribute to related project tasks as required.

## Information for Auditors

The readmes of the higher level directories detail their contents, to aid in finding the relevant files and information. 

In this audit cycle, we have completed the first phase of our project - familiarisation, review and updating the work of the previous team, 
a full project analysis including scheduling, risk assessment and mitigation as well as assigning new work packages and allocation of these to team-members, and 
reviewing previous feedback that we have received.

We have begun the second phase, which involves the initial work on the different work packages, with initial CAD models already completed, and Electrical, Cooling, and Vibration 
analysis well underway.

To get an understanding of what the most relevant files are for this (2nd) audit, go to:
[Current Status Directory](https://gitlab.cecs.anu.edu.au/u5568225/GuidestarLaser/tree/master/Current_Status) 
and read the **Weekly_And_Audit_Summaries.pdf** file.  This will guide you through where to go, what to look at, and what they are.


## Contents

* **Client Communications**: contains all one-way communication with the client, 
including **emails** and **information provided**. This does not include the transcripts
of meetings held with the client present, which are instead in the 
"Meeting Minutes".

* **Current Status**: contains key documents showing the current status of the
project; the **calendar** shows key upcoming dates, while the currrent work 
section contains a statement of the things that need to be done and areas of
priority up until the next update. Periodically updated as work progresses.
	
* **Meeting Minutes**: contains **minutes** for group meetings,
tutorials, and client meetings.

* **Previous Team Work**: this directory effectively contains the entirety of the
**previous group's repository** on this project, to be used as reference material
for our continuation of their work. The readme file within this repository
contains the contents and breakdown, in order to avoid oversaturating this file.

* **Project Deliverables**: this directory contains **techincal project documents**, **requirements** and
deliverables. Confidential documents are not available for viewing, however
a brief description is provided in the readme file. 