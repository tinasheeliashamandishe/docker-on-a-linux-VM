<h1>Configure Docker</h1>

<h2>Description</h2>
This lab will Configure Docker on a Linux VM and install a container running the Nginx server..<br /><br />
A container, in computing, refers to a lightweight, standalone, executable package that includes everything needed to run a piece of software, including the code, runtime, system tools, system libraries, and settings. Containers are often compared to virtual machines (VMs), but they are more lightweight because they share the host system's kernel and do not require a separate operating system instance for each application.
<br /><br />
The most popular containerization platform is Docker, which uses containerization technology to create and manage containers. Containers offer several advantages, including portability, consistency across different environments, and efficient resource utilization. They are commonly used in software development, deployment, and scaling applications in cloud computing environments.


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Step 1</h4>
Spin up a Linux VM<br/>
<img src="https://i.imgur.com/QjY0N1F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Step 2</h4> 
Connect to the VM, install Docker.<br/>
Verify the installation.
<img src="https://i.imgur.com/b4pG3hZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<br />

<h4>Step 3</h4> 
Download a conatiner Image from Docker Hub and the run image.<br/>
Verify that the conatiner is launched.
<img src="https://i.imgur.com/tY4H5jD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

Access your Container via HTTP, You should be able to access the Nginx server.\.<br/>
<img src="https://i.imgur.com/OytEyvW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

