###Add/Modify Policy:
The process which allows a manager to add, modify or view policy information stored in the ‘Software Package License & Vulnerability Data Store’.

###Developer:  
A primary actor in the dataflow diagram.  Able to submit software for scanning, view policies, and access the ‘Manager License & Vulnerability Interface’. Receives results of policy requests and software scanning.

###License & Vulnerability Information: 
Relevant data about a license and/or vulnerability which can be submitted to the ‘Manager License & Vulnerability Interface’ to see if it exists in that process.

License Results: 
Data which originates in the ‘Scan for Licenses’ process and is the result of a scan of a software package for any license information contained within.

List all Package & License Info: 
Composite data originating from the vulnerability & license information data store and ending in the ‘Manager License & Vulnerability Interface’.  When a manager requests ‘Software Project License & Vulnerability Information’ from the ‘Manager License & Vulnerability Interface’, this is the complete vulnerability & license information data which is then made available to the manager. 

Manage Software for License Scanning: 
A process which accepts software packages from the developer and submits the package to both the ‘Scan for Licenses’ process and the ‘NIST Vulnerabilities’ data store and then compiles the results to return to the developer.

Manager: 
A primary actor in the data flow diagram that works independently of the only other primary actor, the developer.  The manager is unable to submit software packages for scanning, but is able to access the results of scans and view license and vulnerability information.  The manager is also the only entity which can add or modify policies relating to software scanning.

Manager License & Vulnerability Interface:
The management information system which allows a manager to view the complete results of a software scan that a developer has run.  The interface retrieves this data from the ‘Vulnerability & License Information’ data store.

NIST Vulnerabilities DB: 
An online data store which is a repository of known vulnerabilities in software.  When a developer submits a new program for scanning, the data is checked against this data store and the results, a list of known vulnerabilities, returned to the developer.

Policy Data: 
This is information relating to policies which exist around the process of software scanning.  This could be data that is being added as a new policy, data that is a modification of an existing policy or simply data that is sent to see if a policy exists within the ‘Software Package License & Vulnerability Policy’ data store.

Policy Information:
This is the information that a developer or manager submits to determine if the policy they described exists within the ‘Software Package License & Vulnerability Policy’ data store.

Policy Request: 
Information about a policy which a developer submits to see if that policy exists within the ‘Software Package License & Vulnerability Policy’ data store via the ‘Request Policy’ process.

Request Policy: 
The policy which connects to the ‘Software Package License & Vulnerability’ data store.  A developer or manager is able to access this process to determine whether a policy that they describe exists in the policy data store.

Request Software Project License & Vulnerability Information: 
The dataflow in which the ‘Manager License & Vulnerability Interface’ collects the complete data on vulnerability & license information from the data store of the same name.

Scan for Licenses:
This is the process where a software package submitted by a developer is scanned to determine if there is any licenses contained within the software, including GPL, MIT or any other types of licenses.

Software Package Name:  
A dataflow which take the name of the software package submitted by a developer and enters it into the online ‘NIST Vulnerabilities’ data store to determine if that particular piece of software has any known vulnerabilities.

Software Package:  
The software itself, submitted by the developer for scanning.

Software Pkg. License & Vulnerability Policy: 
A data store which contains the complete information on all policies existing within the organization.

Software Pkg. License & Vulnerability Results: 
Information on the licenses & vulnerabilities that were determined by the original software scan.  This information is returned to the developer and to the manager via the ‘Manager License & Vulnerability Interface”.

Vulnerability & License Information: 
A data store which contains the complete license and vulnerability information from scans run by the developer.

Vulnerability Results:  
This is the data flow of results from the ‘NIST Vulnerabilities” data store which returns to the ‘Manage Software for License Scanning’ process and eventually reaches both developer and manager.
