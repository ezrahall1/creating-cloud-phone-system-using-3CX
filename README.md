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























<H3>Step 2 – Enable static website hosting </H3>
Click on the name of your bucket, then click on properties scroll down to the bottom where it says static website hosting and click on edit. Click on enable and make sure host a static website is selected.
<img src="https://i.imgur.com/D92cAzu.png" height="80%" width="80%" alt="Image 4"/>
<br />
<br />
In the index document section make sure you have added index.html and error.html in the correct text area, click save changes.
<img src="https://i.imgur.com/agU4L6a.png" height="80%" width="80%" alt="Image 6"/>
<br />
<br />
Scroll down to static website hosting section and make a note of your bucket URL.
<img src="https://i.imgur.com/bCb30OR.png" height="80%" width="80%" alt="Image 7"/>

The next step is to upload some objects to the bucket you have created. In order to do that you would need to scroll to the top of the page and click on objects, then click on upload.

Click on upload, click on add files and add the two html files (index.html and error.html). 
<img src="https://i.imgur.com/AQICKJI.png" height="80%" width="80%" alt="Image 8"/>
<H3>Step 3 – Grant permissions</H3>
The next step is you need to grant permissions to be able to read these objects. You would need to create a bucket policy. Click on the permission tab scroll down to where is says bucket policy click on edit. When entering the policy details remember to update the arn so it is not the same as mine or else it would not work, click on save changes.
<img src="https://i.imgur.com/mlZjKBx.png" height="80%" width="80%" alt="Image 9"/>
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
