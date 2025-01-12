Project Overview-
The project involved deploying a multi-tier containerized web application on a Kubernetes cluster. The goal was to ensure high availability,
scalability, fault tolerance, and seamless deployment across different environments, leveraging Kubernetes' powerful orchestration capabilities.

![image alt](https://github.com/RameshJaiswal/vprokube/blob/e4bb58f7b477720ae0c3233e339ebc8b8847747d/Screenshot%20(371).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(374).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(376).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(378).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(383).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(386).png)


Key Steps and Objectives:

Domain and DNS Configuration:
Registered domain with GoDaddy (e.g., groophy.in).

![image alt](https://github.com/RameshJaiswal/vprokube/blob/2f9bb5a5fc3a1a9d288bd846b203e897dfc1308a/Screenshot%20(369).png)

Configured DNS records and subdomains using AWS Route 53.

![image alt](https://github.com/RameshJaiswal/vprokube/blob/d857c432c99abc50325682f48216d5c421f23631/Screenshot%20(348).png)

Kops and Kubernetes Setup:
Launched an Ubuntu EC2 instance as the base machine for Kops setup.
Installed necessary tools including Kops, kubectl, SSH keys, and AWS CLI.
Configured AWS CLI with IAM user credentials for administrative access.


![image alt](https://github.com/RameshJaiswal/vprokube/blob/c3d94045cd13b2ba4e693f4b738094059f32db4b/Screenshot%20(346).png)

Infrastructure Setup:
Created an S3 bucket and set up a Route 53 hosted zone for the subdomain.
Configured security groups and launched an EC2 instance to run Kops commands.
Installed Kops and kubectl, and generated SSH keys for secure communication.

![image alt](https://github.com/RameshJaiswal/vprokube/blob/d381d0a050a9cb0decdd0a80636fad80b8c16fef/Screenshot%20(351).png)

Cluster Deployment:
Deployed the Kubernetes cluster using Kops commands.
Ensured high availability and fault tolerance through auto-scaling and self-healing mechanisms.
![image alt](https://github.com/RameshJaiswal/vprokube/blob/fc886f8944731d4f8491b2d7545c0ba4c499aa9f/Screenshot%20(352).png)

Cloning Source code from GitHub Repository:
![image alt](https://github.com/RameshJaiswal/vprokube/blob/c0975fdf32e0c8a9cd2a4da5272d7945a3cb6d66/Screenshot%20(354).png)








