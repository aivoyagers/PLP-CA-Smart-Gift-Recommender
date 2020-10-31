# PLP-CA-Smart-Gift-Recommender
A conversational user interface (ChatBot) for the purpose of recommending gifts by Sentiment &amp; Aspect mining of user reviews
﻿## SECTION 1 : PROJECT TITLE
## Intelligent Rapid Shuttle (IRS) System


<img src="images/gift.png"
     style="float: left; margin-right: 0px;" /> 
<!---
<img src="SystemCodes/static/IRS-Vehicle.png"
     style="float: left; margin-right: 0px;" width="400" /> <img src="SystemCodes/static/IRS-Systems-Architecture.png"
     style="float: left; margin-right: 0px;" width="400" />
-->
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
The objective was to build a smart gift recommender chatbot which would:
*1.	Recommend gifts based on a few user parameters. The recommendation would be based on the user intent, aspects of the product, sentiment analysis of the reviews and the ratings given to the product.

*2.	List the top 5 gift products with price and features and the website link.
This would simplify the user decision making and also help them to have a pleasant shopping experience.


---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | Email (Optional) |
| :------------ |:---------------:| :-----| :-----|
| SUDALAIANDI RAJA SUDALAIMUTHU | A0195338U |OptaPlanner Solver configuration, Class Diagram, Data Model, Drools Rules development for Constraints, Systems Architecture, Project video, Input Data Preparation and revision to Report, Userguide and Readme | E0384969@u.nus.edu |
| JAYARAMAN REVATHI | A0195357R | Webpage Design and Client Side Programming, Google Map Plotting, Integration of webpage to KIE Server | E0384988@u.nus.edu |
| JAYASRI RAGHUNATHAN | A0005978U | ParseHub Web Scraping, Randomize Input data generation, Async Javascript web Client Programming | E0384183@u.nus.edu |
| SUNIL VARGHESE | A0195247W | Final Submission Report, User Guide, Readme  | E0384878@u.nus.edu |


---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO
[![IRS Intelligent Rapid Shuttle](SystemCodes/static/IRS-Output.jpg)](https://youtu.be/W3MZEjSZb8A "IRS Shuttle Service")
Click the image above to view Video. Alternatively, you can view following the link https://github.com/aivoyagers/IRS-RS-2019-03-09-IS1PT-GRP-aiVoyagers-irs-Intelligent-Rapid-Shuttle/blob/master/Video/IRSVideo.MOV

---
## SECTION 5 : USER GUIDE
IRS((Intelligent Rapid Shuttle) is a web based shuttle services optimizer. It would be used by the service provider to achieve the shortest overall distance between locations. The routes would be shown visually on the google map to enable the service provider to navigate easily. 

+	git clone https://github.com/aivoyagers/IRS-RS-2019-03-09-IS1PT-GRP-aiVoyagers-irs-Intelligent-Rapid-Shuttle.git
+	Unzip irs-Intelligent-Rapid-Shuttle.zip from SystemCodes folder and Import the project in to KIE
+	Build and Deploy to the execution server of KIE workbench
+	Copy the intelligentrapidshuttle-0.0.1-SNAPSHOT.war file to the JBOSS server by issuing the following command: (Note : change the destination folder specific to your installation of jboss server)
	+ cp SystemCodes/intelligentrapidshuttle-0.0.1-SNAPSHOT.war /home/iss-user/iss-vm-program/is-intelligent-reasoning-systems/jboss/jbpm-server-7.12.0.Final-dist/standalone/deployments/

+	As it uses Google Map services for visualization of Optimization output, please ensure that you are connected to internet. Internet access is required. 
+	This application invokes KIE server and the default userid ‘wbadmin’ and default password is used to signon to KIE. If your wbadmin default password is changed in KIE, please update the program with correct userid and password in the project IRSWeb-intelligentRapidShuttle project from the zip file available in SystemCodes folder. Build and Install on to JBOSS server as required.
	+ (Note : Skip Step 9, if your default password for ‘wbadmin’ is left unchanged in KIE) 
+	Go to web browser and key in the url: 
http://localhost:8080/intelligentrapidshuttle-0.0.1-SNAPSHOT/IRSIndex.jsp
 
---
## SECTION 6 : PROJECT REPORT / PAPER
### Table of Contents

* Executive Summary
* Business Problem Background
* Project Objective
* Project Solution
* Project Scope
* System Features
* Limitations
* Conclusion
* Improvements



---
## SECTION 7 : MISCELLANEOUS

### 7.1 Domain Class Diagram  
<img src="SystemCodes/static/IRS-Class-Diagram.png"
     style="float: left; margin-right: 0px;" /> 

### 7.2 IRS Systems Artchitecture  
<img src="SystemCodes/static/IRS-Systems-Architecture.png"
     style="float: left; margin-right: 0px;" /> 

---
