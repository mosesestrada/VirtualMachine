<p align="center">
 <img src="https://i.imgur.com/URf7txN.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Creating a Virtual Machine in Hyper-V</h1>


<h2>Description</h2>

Are you tired of constantly switching between different computers or systems just to run different operating systems or applications? Virtual machines are here to simplify your life!

Virtual machines allow you to create and run multiple virtual environments on a single physical computer, each with its own operating system and applications. This means no need for extra hardware or the hassle of managing multiple devices.

And the possibilities are endless! Virtual machines are widely used for testing new software, running legacy applications, and creating secure sandboxed environments for various purposes.

Today, I'm excited to showcase how you can create your very own virtual machine using Hyper-V.

<br />

<h2>Environments Used </h2>

 <b>Windows 11 </b> <p>
 <b>Hyper-V</b></p>
<h2>Program walk-through:</h2>

<p align="center">
From the taskbar, select Start.
In the search field, type Hyper-V. Find and select Hyper-V Manager.


<br/>
<img src="https://i.imgur.com/D2juf0T.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
Expand Hyper-V manger and look for the Hyper-V host server. In this example our host is ITAdmin so we will right-click on ITAdmin and select new > Virtual Machine. See example below on how it's supposed to look like.
 <br/>
<img src="https://i.imgur.com/7aHxSNR.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
Name your Virtual Machine. We're keeping it simple today so we will name our Virtual Machine, VM1. Click next.
 <br/>
<img src="https://i.imgur.com/j4X6CxW.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
We will accept the defaults of "generation 1" for this lesson. Click next to continue.

 <br/>
<img src="https://i.imgur.com/9xP1Sad.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
We will be assigning 1024MB of memory for our VM. Click next.
<br/>
<img src="https://i.imgur.com/wjGqYGD.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
We want our VM to be able to communicate with other virtual machines and be able to co communicate outside of our nextwork as well so we will set our network adapter to "External". Click next.

 <br/>
<img src="https://i.imgur.com/TwFVAUV.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
Set your virtual hard disk properties to match my prompt or set your own values then click next.
 <br/>
<img src="https://i.imgur.com/nxoi5zM.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
We will install operating system at a later date. If you have a bootable ISO this is where you would set it up. Click next.
 <br/>
<img src="https://i.imgur.com/LledC30.png" height="80%" width="80%" alt="Add a VM"/>
<br />
<br />
That's it, we're done! Simple, right? Click finished. <br/>
<img src="https://i.imgur.com/nFcdUTk.png" height="60%" width="60%" alt="Add a VM"/>
<br />
<br />
Hope you enjoyed this demonstration. <br/>
<img src="https://i.imgur.com/8wHVar1.jpg" height="80%" width="80%" alt="Add a VM"/>
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
