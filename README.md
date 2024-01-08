<h1>Download Nessus Essentials on VM</h1>


<h2>Description</h2>
In our first tutorial, we set up a Kali Linux virtual machine (VM). In this next tutorial, we will proceed to install Nessus Essentials on our Kali Linux VM. This installation will involve downloading Nessus and subscribing to the free Essentials version. Once the installation is complete, we will log in to Nessus and guide you through the initial setup steps.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Kali Linux</b> 
- <b>Nessus Essentials</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> Oracle VM Virtualbox

<h2>Program walk-through:</h2>

<p align="center">
Launch the shell and type- sudo apt update: <br/>
<img src="https://i.imgur.com/8n7r4Mu.png" height="80%" width="80%" alt="Open you shell and type- sudo apt update."/>
<br />
<br />
Type password:  <br/>
<img src="https://i.imgur.com/uVZ3j97.png" height="80%" width="80%" alt="Type in your Root password."/>
<br />
<br />
Wait for update to complete: <br/>
<img src="https://i.imgur.com/i3C45yA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch your web browser; in this tutorial, we've utilized Firefox. Begin by searching for "Nessus Essentials download" or use the following link:
https://www.tenable.com/downloads/nessus?loginAttempted=true
:  <br/>
<img src="https://i.imgur.com/KJdXxpk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After reaching the download site, ensure that you have selected the latest version by clicking the drop-down menu for "Version." Next, navigate to the "Platform" section and choose the Nessus version compatible with Debian that matches your Kali Linux version. For this tutorial, we're utilizing the "Linux-Debian-amd64" option. Once you've made your selection, click on the "Download" button and agree to the terms and conditions:  <br/>
<img src="https://i.imgur.com/Ca5DXkq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once the download is finished, clear your terminal and navigate to the "Downloads" directory by using the "cd" command:  <br/>
<img src="https://i.imgur.com/ZptPlYh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Employ the "ls" command to inspect the Nessus download in your directory:  <br/>
<img src="https://i.imgur.com/CmwwwGe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Now we're going to run- sudo dpkg -i Nessus-10.6.1-debian_amd64.deb. Type password if needed: <br/>
<img src="https://i.imgur.com/Y6xfP4I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
