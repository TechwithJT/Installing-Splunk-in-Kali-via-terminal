<h1>How To Install Splunk On Kali Linux</h1>


<h2>Description</h2>
In this lab i will be showing you how to install Splunk on a kali linux machine via the linux terminal 
<br />


<h2>Utilities Used</h2>

- <b>Kali Linux install file </b>
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b>

<h2>Download the kali linux package using the link below</h2>

<a href="https://www.splunk.com/en_us/download/splunk-enterprise.html">Splunk Install</a>

<p align="center">
When on this screen download the debian flavor of splunk: <br/>
<img src="https://i.imgur.com/2S5Rtzf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once downloaded open up a terminal shell in kali:  <br/>
 - <b>Type the ls command to "list the contents of a directory or folder and follow the commands below to confirm the download"</b>
<img src="https://i.imgur.com/NLcmjaj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After confirming the splunk is in the download folder lets install using the command below: <br/>
<img src="https://i.imgur.com/FVRgGEs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After running splunk will attempt to install and it should say "unpacking splunk" and just wait:  <br/>
<img src="https://i.imgur.com/wWXQmcU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time) it should look like below:  <br/>
<img src="https://i.imgur.com/Bg7CgBZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />After installing clear the command line using the "clear Command" and rung the "ls /opt command" you should see a fold named splunk:  <br/>
<img src="https://i.imgur.com/aEo2Czr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Starting the splunk service use the following command:  <br/>
 - <b>Just Hold the enter key to get passed the terms of service document and at he end it will ask you to agree to it type y and proceed</b>
<img src="https://i.imgur.com/1EqiXgq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<br />
<br />
Splunk will then attempt to load the web GUI interface for us to login to :  <br/>
<img src="https://i.imgur.com/E6DUhSJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Open up a web browser and type "https://kali:8000" it should bring you to a splunk login screen :  <br/>
 - <b>Note During install process it will prompt you to setup a username and password for this screen</b>
<img src="https://i.imgur.com/7ZarInb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Now you should be logged into Splunk where you can make configurations, install forwarders, or just tamper in a safe environment :  <br/>
 
 - <b>Have Fun</b>
<img src="https://i.imgur.com/Ahcsorv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


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
