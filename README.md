<h1>Setting Up Isolated AWS VPCs and Kubernetes Network Policies with Calico</h1>


<h2>Description</h2>
This project involves setting up isolated VPCs in AWS, configuring secure inter-VPC communication via VPC peering, and implementing Kubernetes network policies using Calico. It ensures a secure cloud infrastructure with controlled pod communication for better security and networking in a multi-VPC setup.
<br />


<h2>Utilities Used</h2>

- AWS EC2
- AWS CLI
- AWS VPC Peering
- kubectl
- Kubernetes
- Calico


<h2>Project Walk-through</h2>

<p align="center">
Isolated VPC Setup in AWS <br />
<img src="https://i.imgur.com/IMQ2aqr.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Subnets <br/>
<img src="https://i.imgur.com/dnqIJh6.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Attach Internet Gateways <br/>
<img src="https://i.imgur.com/PMqonUt.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set Up Route Tables <br/>
<img src="https://i.imgur.com/zmMMQnl.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
VPC Peering for Secure Communication <br/>
<img src="https://i.imgur.com/2WeumoZ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Calico on Kubernetes Cluster for Network Policies <br/>
<img src="https://i.imgur.com/Zp9uQIT.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create and Apply Network Policies for Pod Communication <br/>
<img src="https://i.imgur.com/EYUR8ub.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Testing and Verification
<br/>
<img src="https://i.imgur.com/20rNbPY.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

