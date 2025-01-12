Project Overview-<br>
The project involved deploying a multi-tier containerized web application on a Kubernetes cluster.<br>
The goal was to ensure high availability,scalability, fault tolerance, and seamless deployment across different environments, leveraging Kubernetes' powerful orchestration capabilities.<br>

![image alt](https://github.com/RameshJaiswal/vprokube/blob/e4bb58f7b477720ae0c3233e339ebc8b8847747d/Screenshot%20(371).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(374).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(376).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(378).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(383).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/426746cf13e7365de0f5505a396c5fb6c9c21492/Screenshot%20(386).png)
<br>


Key Steps and Objectives:
<br>
Domain and DNS Configuration:<br>
Registered domain with GoDaddy (e.g., groophy.in).

![image alt](https://github.com/RameshJaiswal/vprokube/blob/2f9bb5a5fc3a1a9d288bd846b203e897dfc1308a/Screenshot%20(369).png)

Configured DNS records and subdomains using AWS Route 53.<br>

![image alt](https://github.com/RameshJaiswal/vprokube/blob/d857c432c99abc50325682f48216d5c421f23631/Screenshot%20(348).png)

Kops and Kubernetes Setup:<br>
Launched an Ubuntu EC2 instance as the base machine for Kops setup.<br>
Installed necessary tools including Kops, kubectl, SSH keys, and AWS CLI.<br>
Configured AWS CLI with IAM user credentials for administrative access.<br>


![image alt](https://github.com/RameshJaiswal/vprokube/blob/c3d94045cd13b2ba4e693f4b738094059f32db4b/Screenshot%20(346).png)

Infrastructure Setup:
Created an S3 bucket and set up a Route 53 hosted zone for the subdomain.<br>
Configured security groups and launched an EC2 instance to run Kops commands.<br>
Installed Kops and kubectl, and generated SSH keys for secure communication.<br>

![image alt](https://github.com/RameshJaiswal/vprokube/blob/d381d0a050a9cb0decdd0a80636fad80b8c16fef/Screenshot%20(351).png)

Cluster Deployment:
Deployed the Kubernetes cluster using Kops commands.<br>
Ensured high availability and fault tolerance through auto-scaling and self-healing mechanisms.<br>
![image alt](https://github.com/RameshJaiswal/vprokube/blob/fc886f8944731d4f8491b2d7545c0ba4c499aa9f/Screenshot%20(352).png)

Cloning Source code from GitHub Repository:<br>
<br>
![image alt](https://github.com/RameshJaiswal/vprokube/blob/c0975fdf32e0c8a9cd2a4da5272d7945a3cb6d66/Screenshot%20(354).png)

Tools and Technologies Used:<br>
Tomcat: Used for running the web application.<br>
MySQL: Managed with PersistentVolumeClaims to maintain data persistence.<br>
Memcached: Deployed for caching to improve performance.<br>
RabbitMQ: Used for message queuing and service communication.<br>
Kubernetes: Orchestrates containerized applications for efficient deployment and resource management.<br>
Ingress Controller (NGINX): Handles external access to the application, with AWS Application Load Balancer for load balancing.<br>
Kops: Helps in provisioning and managing the Kubernetes cluster.<br>
kubectl: Command-line tool for interacting with the Kubernetes cluster.<br>
<br>

![image alt](https://github.com/RameshJaiswal/vprokube/blob/926509e35773a701a2675f06a2018b90b55d47e2/Screenshot%20(400).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/926509e35773a701a2675f06a2018b90b55d47e2/Screenshot%20(401).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/926509e35773a701a2675f06a2018b90b55d47e2/Screenshot%20(402).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/926509e35773a701a2675f06a2018b90b55d47e2/Screenshot%20(403).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/926509e35773a701a2675f06a2018b90b55d47e2/Screenshot%20(404).png)
![image alt](https://github.com/RameshJaiswal/vprokube/blob/926509e35773a701a2675f06a2018b90b55d47e2/Screenshot%20(407).png)
<br>
<br>
Conclusion:
<br>
This project involved deploying a multi-tier containerized web application on a Kubernetes cluster using Kops. It focused on ensuring high availability, scalability, and fault tolerance. Through this project, I gained hands-on experience with Kubernetes, Tomcat, MySQL, RabbitMQ, and other tools to deliver a reliable, scalable solution.<br>
<br>
#Kubernetes #Docker #Containerization #Kops #WebApplication #CloudComputing #Scalability #HighAvailability #DevOps #MySQL #RabbitMQ #Tomcat #CICD #InfrastructureAsCode #Microservices















