
# Deployed Web Applications

**Deployed web applications** refer to web apps that have been made accessible to users by hosting them on servers or cloud platforms. Here’s how AWS services like **EC2** and **Elastic Beanstalk** play a role in deploying web applications:




### 1. **EC2 Instance (Amazon Elastic Compute Cloud)**
   - **What It Is**: EC2 is a cloud service that provides scalable virtual servers (instances) in the AWS cloud. You can use these instances to host web applications, databases, or any software.
   - **How It Works**:
     1. **Launch an Instance**: Start by launching an EC2 instance, which is a virtual server running on AWS. You can choose the operating system, CPU, memory, and storage.
     2. **Deploy Your App**: Install the necessary software (like a web server) on the instance, then upload and configure your web application.
     3. **Access the App**: Once deployed, your application can be accessed via the public IP address or domain name associated with the EC2 instance.
     
![Elastic Beanstalk Advantages](https://k21academy.com/wp-content/uploads/2020/09/Advantage-of-Elastic-Beanstalk.png)  

### 2. **Elastic Beanstalk**
   - **What It Is**: Elastic Beanstalk is a fully managed service that helps developers deploy and manage web applications and services. It automatically handles the infrastructure (EC2 instances, load balancers, scaling, etc.) so you can focus on writing code.
   - **How It Works**:
     1. **Upload Your Code**: You simply upload your application code (e.g., via a ZIP file or a Git repository).
     2. **Choose an Environment**: Select the platform (like Node.js, Python, Java) that your application runs on.
     3. **Deploy**: Elastic Beanstalk automatically provisions resources like EC2 instances, load balancers, and databases, and deploys your application.
     4. **Manage and Scale**: It monitors your app, automatically scales the infrastructure based on demand, and provides tools for updating or rolling back versions.


### Difference:
- **EC2 Instance**: Gives you full control over a virtual server where you manually deploy and manage your web application.
- **Elastic Beanstalk**: Automates the deployment and management process, allowing you to focus more on your code and less on the infrastructure.

Both services allow you to deploy web applications, but they cater to different needs—EC2 for more control and flexibility, Elastic Beanstalk for ease of use and management.
