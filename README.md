<h1>Creating Cloud Phone System Using 3CX</h1>

<h2>Description</h2>
This project demonstrate how to use AWS to host a phone system in the cloud. To stay within the free tier I used 3CX  extension number instead of using Amazon Chime. 
<br />


<h2>Services Used</h2>

- <b>IAM</b> 
- <b>AWS Marketplace</b> 
- <b>3CX Phone System</b> 

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Program walk-through:</h2>
<H3>Step 1 - Create user</H3>

Once I logged into my AWS account I clicked on services>IAM>users then clicked on users to add a new user.

<img src="https://i.imgur.com/ypb9u3Z.png" height="80%" width="80%" alt="Image 1"/>
<br />
<br />

<img src="https://i.imgur.com/vfHCrkI.png" height="80%" width="80%" alt="Image 2"/>

<img src="https://i.imgur.com/ln1BJZL.png" height="80%" width="80%" alt="Image 3"/>

<img src="https://i.imgur.com/MK4P39Q.png" height="80%" width="80%" alt="Image 4"/>
<br />

<img src="https://i.imgur.com/bN71U2V.png" height="80%" width="80%" alt="Image 5"/>

<img src="https://i.imgur.com/o33zyyW.png" height="80%" width="80%" alt="Image 6"/>

<img src="https://i.imgur.com/WuJv7k8.png" height="80%" width="80%" alt="Image 7"/>

<img src="https://i.imgur.com/lkmBYlP.png" height="80%" width="80%" alt="Image 8"/>

<H3>Step 2 – Creating EC2 instance and key pair</H3>

From there I headed over to the EC2 section in order to create the EC2 instance and key pair.

<img src="https://i.imgur.com/gq2nNx2.png" height="80%" width="80%" alt="Image 9"/>

Click on keypair in order to create a keypair. 

<img src="https://i.imgur.com/x4P6v3l.png" height="80%" width="80%" alt="Image 10"/>

Enter the name of the key pair and select pem as the file format, click create key pair.
<img src="https://i.imgur.com/Iy3KGZA.png" height="80%" width="80%" alt="Image 11"/>

<img src="https://i.imgur.com/Vs7NZGf.png" height="80%" width="80%" alt="Image 12"/>

<H3>Step 3 – Subscribe to Debian GNU/Linux 9 (stretch)</H3>
In this section I headed over to the AWS Marketplace in order to install Debian 9 

<img src="https://i.imgur.com/PlUeMjh.png" height="80%" width="80%" alt="Image 13"/>

<img src="https://i.imgur.com/Hb3Aoba.png" height="80%" width="80%" alt="Image 14"/>

<img src="https://i.imgur.com/rJqqksw.png" height="80%" width="80%" alt="Image 15"/>

<img src="https://i.imgur.com/ROdj4Pa.png" height="80%" width="80%" alt="Image 16"/>

<H3>Step 4 – Creating 3CX account</H3>
In this final step I created the 3CX account which can be done from the URL link below:

https://www.3cx.com/phone-system/download-phone-system/

<img src="https://i.imgur.com/6hhhK0i.png" height="80%" width="80%" alt="Image 17"/>

<img src="https://i.imgur.com/CYnj4P4.png" height="80%" width="80%" alt="Image 18"/>

<img src="https://i.imgur.com/FrKQ6on.png" height="80%" width="80%" alt="Image 19"/>

<img src="https://i.imgur.com/XafXYyk.png" height="80%" width="80%" alt="Image 20"/>

<img src="https://i.imgur.com/7A4N68n.png" height="80%" width="80%" alt="Image 21"/>

<img src="https://i.imgur.com/AZz661X.png" height="80%" width="80%" alt="Image 22"/>

<img src="https://i.imgur.com/7tfuXzD.png" height="80%" width="80%" alt="Image 23"/>

<img src="https://i.imgur.com/4WsmKZR.png" height="80%" width="80%" alt="Image 24"/>

<img src="https://i.imgur.com/bCZjiU9.png" height="80%" width="80%" alt="Image 25"/>

<img src="https://i.imgur.com/PrcXQmw.png" height="80%" width="80%" alt="Image 26"/>

<img src="https://i.imgur.com/aNkq6Qf.png" height="80%" width="80%" alt="Image 27"/>

<img src="https://i.imgur.com/voLYfNy.png" height="80%" width="80%" alt="Image 28"/>

This screen shows that 3CX has been successfully configured and I can now login.

<img src="https://i.imgur.com/33zsKxl.png" height="80%" width="80%" alt="Image 29"/>


From there you can download the 3CX app from the Android or iOS store in order to make calls, just use your QR code to configure the settings.

Once you are logged to the admin dashboard you can add more phone extensions, check call history, and configure it to your requirement.

<img src="https://i.imgur.com/nulH8d6.png" height="80%" width="80%" alt="Image 30"/>

</p>
