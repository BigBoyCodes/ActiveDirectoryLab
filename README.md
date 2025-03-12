<h2>Description</h2>
<p>In this lab, I successfully set up a fully functional Active Directory environment on my personal computer using VMware. The process of configuring and running this lab significantly deepened my understanding of Active Directory and Windows networking as a whole. This hands-on experience provided valuable insights into domain management, user authentication, and network communication, reinforcing key concepts in a practical way.</p>



<h2>Environments Used</h2>
<ul>
    <li><b>Microsoft Server 2019</b></li>
    <li><b>Windows 10</b></li>
    <li><b>VMware</b></li>
</ul>

<h2>Program Walkthrough</h2>

<h3>Part 1 - Setting Up IP Addressing</h3>
<img src="https://i.imgur.com/2EgDBag.png" width="80%" alt="ActiveDirectoryLab">
<p>In this step, we first identify which adapter is connected to the internet (<code>INTERNET</code>) and which one is used for internal communication (<code>x_internal_x</code>). The adapter assigned a random IP address indicates an internal connection. We then assign a static IP address to the Internal NIC.</p>
<img src="https://i.imgur.com/fXV2OVM.png" width="80%" alt="ActiveDirectoryLab">

<h3>Part 2 - Renaming the PC</h3>
<img src="https://i.imgur.com/jBWutTk.png" width="80%" alt="ActiveDirectoryLab">
<p>We rename the machine to <b>DC</b> (Domain Controller) to reflect its role in the network.</p>

<h3>Part 3 - Installing Active Directory Domain Services (AD DS)</h3>
<img src="https://i.imgur.com/bM9UQMt.png" width="80%" alt="ActiveDirectoryLab">
<p>After installing AD DS, I created my domain <b>mydomain.com</b> and set up a domain administrator password.</p>

<h3>Part 4 - Creating a Dedicated Domain Admin Account</h3>
<img src="https://i.imgur.com/SEepFDc.png" width="80%" alt="ActiveDirectoryLab">
<p>We create a dedicated domain account and grant it administrative privileges.</p>
<img src="https://i.imgur.com/rG83Yvk.png" width="80%" alt="ActiveDirectoryLab">

<h3>Part 5 - Configuring Routing and Remote Access</h3>
<img src="https://i.imgur.com/mHzWxmI.png" width="80%" alt="ActiveDirectoryLab">
<p>We install <b>NAT (Network Address Translation)</b> to allow communication between the internal network and external networks.</p>
<img src="https://i.imgur.com/p3vPtvh.png" width="80%" alt="ActiveDirectoryLab">

<h3>Part 6 - Setting Up a DHCP Server on the Domain Controller</h3>
<img src="https://i.imgur.com/ltXTP6T.png" width="80%" alt="ActiveDirectoryLab">
<p>We configure <b>DHCP</b> to assign IP addresses dynamically within the network.</p>
<img src="https://i.imgur.com/G8pK3hx.png" width="80%" alt="ActiveDirectoryLab">

<h3>Part 7 - Creating Users Using PowerShell</h3>
<img src="https://i.imgur.com/7mVYXrn.png" width="80%" alt="ActiveDirectoryLab">
<p>We use PowerShell commands to create multiple users efficiently within Active Directory.</p>
<img src="https://i.imgur.com/ex72cj2.png" width="80%" alt="ActiveDirectoryLab">

<h3>Part 8 - Running Windows 10 and Verifying Network Connectivity</h3>
<img src="https://i.imgur.com/RWfklIL.png" width="80%" alt="ActiveDirectoryLab">
<p>A successful ping confirms that the DNS server is operational. This verifies that the domain controller properly forwards requests to the internet and handles NAT correctly.</p>
<img src="https://i.imgur.com/YDo7u6P.png" width="80%" alt="ActiveDirectoryLab">
<img src="https://i.imgur.com/NNsdoyO.png" width="80%" alt="ActiveDirectoryLab">

<h3>Part 9 - Verifying Windows 10 Membership in the Domain</h3>
<img src="https://i.imgur.com/qZnJCod.png" width="80%" alt="ActiveDirectoryLab">
<p>We confirm that Windows 10 has successfully joined the domain and can authenticate with Active Directory.</p>
<img src="https://i.imgur.com/YDo7u6P.png" width="80%" alt="ActiveDirectoryLab">
<img src="https://i.imgur.com/evGrdWb.png" width="80%" alt="ActiveDirectoryLab">

<p>This lab provided an in-depth understanding of Active Directory infrastructure, networking, and domain management, enhancing my practical skills in IT administration. 🚀</p>
