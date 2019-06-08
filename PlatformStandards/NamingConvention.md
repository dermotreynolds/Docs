

##Naming Convention Standards for Compute 

Virtual Machines in Microsoft Azure have two unique names – VM name and Host name. When a machine is created in portal it uses the same name for both VM name and Host name. So the actual resource name can have up to 64 characters but for domain join with Active directory it is required for hostnames to be setup for 15 characters for both Windows and Linux machines 

 

###Naming Structure for Host names (Windows & Linux) 

The convention consists of 6 separate segments and limits the maximum name size that is within scope of the total numbers of characters allowed for host name.  Below is an overview of how the name is broken down. 

Please note although shown as upper CASE implied this is only to emphasizes the point in Azure we will use lower case.  

 

####PPP/LLL/EE/O/AAA/NNN 

Segment 	 | 	Name 	 | 	Example 
------------	 | 	------------	 | 	------------
PPP 	 | 	Portfolio 	 | 	Dot (dotcom), mtp (mainframe transformation program), fod (foods) 
LLL 	 | 	Region 	 | 	eun 
EE 	 | 	Environment 	 | 	pt (performance test), pr (production), si (system integration testing), st (system testing), dv ( development), pp(pre-prod), ft (functional testing) 
O 	 | 	Operating System 	 | 	L (Linux), w (Windows) 
AAA 	 | 	Application Name 	 | 	pma First two digits for the Application name - pm (PIM Application) 3rd digit for categorizing whether it’s - application server – a , db server – d, web server - w, file server - f  
NNN 	 | 	Count 	 | 	001 - 999 
