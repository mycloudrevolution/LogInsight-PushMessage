<a name="Title">
# Title

PSvLIMessage PowerShell Module

|Navigation|
|-----------------|
|[About](#About)|
|[Features](#Features)|



<a name="About">
# About
[*Back to top*](#Title)

Project Owner: Markus Kraus

Project WebSite: bit.ly/1YXY2gq

Project Details:

PSvLIMessage allows you to Push Messages to VMware vRealize LogInisght via API  


<a name="Features">
# Features
[*Back to top*](#Title)

+ Example Simple

Push-vLIMessage -vLIServer "loginsight.lan.local" -vLIAgentID "12862842-5A6D-679C-0E38-0E2BE888BB28" -Text "My Test"
	
+ Example Extendet

Push-vLIMessage -vLIServer "loginsight.lan.local" -vLIAgentID "12862842-5A6D-679C-0E38-0E2BE888BB28" -Text "My Test" -Hostname MyTEST -FieldName myTest -FieldContent myTest