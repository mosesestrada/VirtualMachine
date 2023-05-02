<p align="center">
 <img src="https://i.imgur.com/OFMboaL.jpg" height="60%" width="60%" alt="Raid Array logo"/>
</p>

<h1>Adding a user in Active Directory</h1>


<h2>Description</h2>

Are you tired of constantly switching between different computers or systems just to run different operating systems or applications? Virtual machines are here to simplify your life!

Virtual machines allow you to create and run multiple virtual environments on a single physical computer, each with its own operating system and applications. This means no need for extra hardware or the hassle of managing multiple devices.

And the possibilities are endless! Virtual machines are widely used for testing new software, running legacy applications, and creating secure sandboxed environments for various purposes.

Today, we're excited to showcase how you can create your very own virtual machine using Hyper-V.

<br />

<h2>Environments Used </h2>

 <b>Windows 11 Pro</b> 

<h2>Program walk-through:</h2>

<p align="center">
From the taskbar, select Start.
In the search field, type Hyper-V.Find and select Hyper-V Manager.


<br/>
<img src="https://i.imgur.com/XNaJ8pL.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Expand Hyper-V maanger and hostname. In this example our hostname is ITAdmin so we will right-click on ITAdmin and select new > Virtual Machine. See example below on how it's supposed to look like.
 <br/>
<img src="https://i.imgur.com/pnwGZ5d.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Expand your domain controller folder which in this case is CorpNet.xyz and for this user we will be adding him to Sales>Users OU.
To do this Highlight "users" under Sales, right click > new> user. Follow the arrows I have posted in the picture below.
 <br/>
<img src="https://i.imgur.com/tcT2KPW.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Name your Virtual Machine. We're keeping it simple today so we will name our Virtual Machine, VM1.

 <br/>
<img src="https://i.imgur.com/ouISQIg.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Add a password for your user and click next.
<br/>
<img src="https://i.imgur.com/gwKXMTm.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Click finished.

 <br/>
<img src="https://i.imgur.com/xz1ElLI.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Now to configure thier logon hours. Right click  the user and select properties.
 <br/>
<img src="https://i.imgur.com/SXHpnbX.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Here you can adjust the user's logon hours. The blue bars are the hours the user can operate his workstation. 
 <br/>
<img src="https://i.imgur.com/AdulRWU.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
That's it, we're done! Simple, right? <br/>
<img src="https://i.imgur.com/9cuTjD2.png" height="60%" width="60%" alt="Adduser"/>
<br />
<br />
Hope you enjoyed this demonstration. <br/>
<img src="https://i.imgur.com/3gMbo9H.jpg" height="60%" width="60%" alt="Adduser"/>
<br />
<br />



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
