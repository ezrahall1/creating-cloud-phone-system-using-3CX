<h1>Creating Cloud Phone System Using 3CX</h1>

<h2>Description</h2>
This project is about how I set up 3CX phone system in AWS. I have provided a guide showing what to do every step of the way.
<br />


<h2>Services Used</h2>

- <b>IAM</b> 
- <b>AWS Marketplace</b> 
- <b>3CX Phone System</b> 

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Program walk-through:</h2>
<H3>Step 1 - Create user</H3>

Once you have logged into the AWS account you would need to click on services>IAM>users. Click on users to add a new user.
<img src="https://i.imgur.com/ypb9u3Z.png" height="80%" width="80%" alt="Image 1"/>
<br />
<br />
Click on add user (this account will be used for 3CX)
<img src="https://i.imgur.com/vfHCrkI.png" height="80%" width="80%" alt="Image 2"/>

Enter a username and tick programmatic access, click next permissions.
<img src="https://i.imgur.com/ln1BJZL.png" height="80%" width="80%" alt="Image 3"/>

Click on attach existing policies directly
<img src="https://i.imgur.com/MK4P39Q.png" height="80%" width="80%" alt="Image 4"/>
<br />
The user you have created would need access to the EC2. You would need to search for AmazonEC2FullAccess and select it and click next:tags
<img src="https://i.imgur.com/bN71U2V.png" height="80%" width="80%" alt="Image 5"/>

Skip the tags section by clicking next:review
<img src="https://i.imgur.com/o33zyyW.png" height="80%" width="80%" alt="Image 6"/>


Click on create user

<img src="https://i.imgur.com/WuJv7k8.png" height="80%" width="80%" alt="Image 7"/>

Before you click close make sure you have downloaded the .csv credentials.
<img src="https://i.imgur.com/lkmBYlP.png" height="80%" width="80%" alt="Image 8"/>

<H3>Step 2 – Creating EC2 instance and key pair</H3>
From there you would need to head over to the EC2 section and make sure you select the region closest to where you live.

<img src="https://i.imgur.com/gq2nNx2.png" height="80%" width="80%" alt="Image 9"/>

Click on keypair in order to create a keypair. 

<img src="https://i.imgur.com/x4P6v3l.png" height="80%" width="80%" alt="Image 10"/>

Enter the name of the key pair and select pem as the file format, click create key pair.
<img src="https://i.imgur.com/Iy3KGZA.png" height="80%" width="80%" alt="Image 11"/>

Key pair would have automatically downloaded to your machine (keep it safe as there is no way to get it back if lost).
<img src="https://i.imgur.com/Vs7NZGf.png" height="80%" width="80%" alt="Image 12"/>

<H3>Step 3 – Subscribe to Debian GNU/Linux 9 (stretch)</H3>
You would need to head over to the AWS Marketplace click on manage subscriptions.
Click on discover products

<img src="https://i.imgur.com/PlUeMjh.png" height="80%" width="80%" alt="Image 13"/>



Based on the policy you have created you will now see a red banner stating, “publicly accessible”, which means the bucket can be access by anyone.

<img src="https://i.imgur.com/PGbBV1i.png" height="80%" width="80%" alt="Image 10"/>

This shows that I successfully created a static website in AWS
<img src="https://i.imgur.com/c8KFtkW.png" height="80%" width="80%" alt="Image 10"/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
