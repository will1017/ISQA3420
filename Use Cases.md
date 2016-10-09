#USE CASE 1

##Title: Determine License and Vulnerability Information 

###Primary Actor:
Corporate Manager

###Goal in Context:
The corporate manager is able to determine license and vulnerability 
information from provided project information

###Stakeholders: 

Corporate Manager: To receive clear and relevant project information

Corporate Developer: To provide the relevant file/package level information 

Project Owner: To clearly understand corporate manager decisions to green/red light a project 

###Preconditions: 

Relevant file/package information is in the SPDX database

Proper project information has been provided  

###Main Success Scenario:
Corporate manager receives accurate license and vulnerability 
information for the requested project packages

###Failed End Conditions:
Corporate manager receives inaccurate or invalid license and 
vulnerability information for the requested project packages

###Trigger: 
Corporate manager uploads or identifies project information to which license and 
vulnerability information is provided

#USE CASE 2

##Title: Upload Software to Scan

### Primary Actor:
Developer

###Goal in Context:
Upload software packages in order to scan for licenses and vulnerabilities

###Stakeholders:

Corporate Manager: To receive clear and relevant project information

Corporate Developer: To provide the relevant file/package level information 

Project Owner: To clearly understand corporate manager decisions to green/red light a project

###Preconditions:

Correct Information Provided (Detail needed -- what type of information?)

Upload Successful -- of package? 

Scanner Operational -- scanner of what?? You need to be a bit more explicit in these preconditions. 

###Main Success Scenario:

Software uploaded to scanning software & results returned to developer (don't forget about vulnerabilities)

###Failed End Conditions:

Software failed to upload, scanning software unable to process package

###Trigger:

Devloper has package to be uploaded

#USE CASE 3

##Title: Developer checks system to see if software has already been uploaded/scanned (This use case is not currently supported in your DFD. Below you are talking about policy. Is this a policy use case or one about checking to see if software has been scanned? This isn't clear). 

###Primary Actor:
Developer

###Goal in Context: 
To determine if a policy exists in the policy datastore

###Stakeholders:
Developer: To provide the policy information to determine if it a policy that exists or needs to be added.

###Preconditions:

Policy information complete
Policy datastore is accessable

###Main Success Scenario:
Relevant policy information retrieved

###Failed End Conditions:
Datastore fails to return results
Policy does not exist

###Trigger:
Developer submits a policy to check if it exists in the system
