### Welcome to the OWASP Top Ten 2004

The OWASP Top Ten provides a powerful awareness document for web application security. The OWASP Top Ten represents a broad consensus about what the most critical web application security flaws are. Project members include a variety of security experts from around the world who have shared their expertise to produce this list. There are currently versions in English, French, Japanese, and Korean. A Spanish version is in the works. We urge all companies to adopt this awareness document within their organization and start the process of ensuring that their web applications do not contain these flaws. Adopting the OWASP Top Ten is perhaps the most effective first step towards changing the software development culture within your organization into one that produces secure code. 

Top Ten Overview

The following list summarizes the OWASP Top Ten. However, we strongly recommend reading the full report, as each area covers quite a lot of ground.

* [A1 2004 Unvalidated Input](https://www.owasp.org/index.php/A1_2004_Unvalidated_Input)

Information from web requests is not validated before being used by a web application. Attackers can use these flaws to attack backend components through a web application. 

* [A2 2004 Broken Access Control](https://www.owasp.org/index.php/A2_2004_Broken_Access_Control)

Restrictions on what authenticated users are allowed to do are not properly enforced. Attackers can exploit these flaws to access other users' accounts, view sensitive files, or use unauthorized functions.

* [A3 2004 Broken Authentication and Session Management](https://www.owasp.org/index.php/A3_2004_Broken_Authentication_and_Session_Management)

Account credentials and session tokens are not properly protected. Attackers that can compromise passwords, keys, session cookies, or other tokens can defeat authentication restrictions and assume other users' identities. 

* [A4 2004 Cross Site Scripting](https://www.owasp.org/index.php/A4_2004_Cross_Site_Scripting)

The web application can be used as a mechanism to transport an attack to an end user's browser. A successful attack can disclose the end user?s session token, attack the local machine, or spoof content to fool the user. 

* [A5 2004 Buffer Overflow](https://www.owasp.org/index.php/A5_2004_Buffer_Overflow)

Web application components in some languages that do not properly validate input can be crashed and, in some cases, used to take control of a process. These components can include CGI, libraries, drivers, and web application server components. 

* [A6 2004 Injection Flaws](https://www.owasp.org/index.php/A6_2004_Injection_Flaws)

Web applications pass parameters when they access external systems or the local operating system. If an attacker can embed malicious commands in these parameters, the external system may execute those commands on behalf of the web application. 

* [A7 2004 Improper Error Handling](https://www.owasp.org/index.php/A7_2004_Improper_Error_Handling)

Error conditions that occur during normal operation are not handled properly. If an attacker can cause errors to occur that the web application does not handle, they can gain detailed system information, deny service, cause security mechanisms to fail, or crash the server. 

* [A8 2004 Insecure Storage](https://www.owasp.org/index.php/A8_2004_Insecure_Storage)

Web applications frequently use cryptographic functions to protect information and credentials. These functions and the code to integrate them have proven difficult to code properly, frequently resulting in weak protection. 

* [A9 2004 Application Denial of Service](https://www.owasp.org/index.php/A9_2004_Application_Denial_of_Service)

Attackers can consume web application resources to a point where other legitimate users can no longer access or use the application. Attackers can also lock users out of their accounts or even cause the entire application to fail. 

* [A10 2004 Insecure Configuration Management](https://www.owasp.org/index.php/A10_2004_Insecure_Configuration_Management)

Having a strong server configuration standard is critical to a secure web application. These servers have many configuration options that affect security and are not secure out of the box. 
