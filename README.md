# GCPCloudArmor



Creating Resources and Setting up Cloud Armor:



1.  Creating a VM with nginx 

Creating a VM with nginx installed


	

VM Created













Creating an Unmanaged Instance Group:







				












Creating a Load Balancer:




			Testing the Nginx site after Load Balancer Creation:











	2: Setting up Cloud Armor Rules

			Creating new Rule to Deny-All Traffic



			Nginx Site after Rule is made



			









Creating Allow-All Rule










			Nginx site after Allow-All Rule:




3. Adding Rule for Cloud shell IP

 		Allowing Cloud Shell IP only





			



4. Setting up more Rules for Access and Denial

Creating a GoodPath folder and BadPath folder then nano index.html




			

Navigating to the Goodpath


			Navigating to the Badpath





Creating Rule to Deny Badpath:




Testing New Rule for Badpath


Testing New Rule for Goodpath






