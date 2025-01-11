# Setting-up-a-metasploitable-virtual-home-lab

<h2>Download And install Metasploitable</h2>

Metasploitable is an intentionally vulnerable Linux virtual machine. This VM can be used to conduct security training, test security tools, and practice common penetration testing techniques.The first step is to download Metasploitable 2 VM<a href=(https://sourceforge.net/projects/metasploitable/)>Click here</a>


<img src="Folder/Capture.PNG">








<h2>Extract the Metasploitable File</h2>

Make sure you extract the metasploitable file which originally comes in a zip file.


<img src="Folder/Extract Meta.PNG">









Right click and extract all


<img src="Folder/Extration done.PNG">








<h2>Open VirtualBox</h2>

On your computer launch virtualbox make sure virtualbox has been installed on your computer if you've not, I have created a guide on how to do that click here (https://github.com/Femi3x/Setting-up-a-virtual-home-lab#)  We can do this by clicking the New button within the VirtualBox Manager.


<img src="Folder/New.jpg">








After clicking on new we are going to get a POP up whereby need to create our virtual machine.


<img src="Folder/Vm2.PNG">










Note: name can be anything of choice, type should be Linux, subtype should be Linux 2.4 and Version should be Linux 2.4(64-bit). After that click finish.


<h2>Memory Size</h2>

The recommended memory size is 512MB. Always note that the blue notification should never move past the green meters.


<img src="Folder/Allocate memory.png">







<h2>Virtual Hard Disk</h2>

Now move to storage and choose Existing hard disk note: be careful during this configuration.


<img src="Folder/Existing HDD.png">








<h2>Configure The Networe</h2>
Ensure that your network settings are configured appropriately. It's recommended to use NAT or Host-only network settings to keep the VM isolated from public networks, as Metasploitable should never be exposed to untrusted networks.



<img src="Folder/network.jpg">









<h2>Add File</h2>

Now add and locate the previously extracted metasploitable file. Make sure the file is vmdk file this is very important if not done properly an error will occur.



<img src="Folder/step 5.jpg">









<h2>Start Metasploitable</h2>
Now go back to the Virtual machine environment and make sure you click on metasploitable after that click on the start interface.


<img src="Folder/Screenshot (6)_LI.jpg">








<h2>Run Metasploitable</h2>

After clicking on the start option metasploitable will start running and it’s going to ask you for Administrative credentials which by default is.
Default loggin:msfadmin
Default password:msfadmin



<img src="Folder/Screenshot (8).png">




Now your metasploitable vulnerability virtual machine ready for you to practice penetration testing, vulnerability assessment, and exploit development in a safe, controlled environment.








