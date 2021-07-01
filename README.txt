File structure:
 - CSS
	- Has all the required style sheets 
 - images
	- Contains images required in the project 
 - js
	- Contains Javascripts required in the project
 - webfonts
    - Contains icons and other fonts 
 - features.html
	- HTML file for feature details 
 - index.hmtl 
	- HTML for home page 
 - pricing.html 
	- HTML for Pricing page 
 - privacy-policy.html 
	- HTML for Privacy Policy 
 - terms-conditions.html 
	- HTML for terms page 
-  blogs.html
	- HTML for blogs page
-  blogs-detail.html
	- HTML for blogs detail page
-  about-us.html
	- HTML for about us page
- demo.html
	- HTML for demo page
	
Hosting details:
	- Hosted in nGinx server @ 13.232.54.21 
	- path: /var/www/html 

Deployment:
	- Server can be connected via WiSCP or FileZilla 
	- Once connected the modified files/folder can be moved to the path specified above

Connecting to server:
	- Server can be connected as per the article below:
	https://winscp.net/eng/docs/guide_amazon_ec2
	- Steps are same for EC2 or Lightsail
	
Server Restart
	- Server can be restarted, if required by below command
	"sudo systemctl restart nginx"
	
