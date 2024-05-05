# Capstone-Project AWS


# Project Overview:
Walker Marque is tasked with designing a solution using Amazon Web Services (AWS) to separate different parts of their application (like the front-end, back-end, and database) and to host both the application and data analysis in the cloud. They also need to ensure that the system stays up and running even if there are technical issues, unlike their current setup which can go down during power outages.


# Customer Requirements:

1. Separate different parts of the application.
2. Host both application and data analysis in the cloud.
3. Ensure the system stays operational even during technical problems.


# Proposed AWS Services:

1. Three-Tier Architecture:
   
# Frontend (HTML, CSS, JavaScript):

* Use Amazon S3 to store website files like HTML, CSS, and JavaScript. It's like a really big and reliable storage box for website stuff.
  
* Employ Amazon CloudFront to deliver these files quickly to users worldwide. It acts like a super-fast delivery system for website content.
  
# Backend (Apache Web Server and Java application):

* Implement an Application Load Balancer (ALB) to evenly distribute user traffic among multiple servers, ensuring the website stays accessible even if one server goes down.
  
* Host the Apache Web Server and Java application on Amazon EC2 instances, which are like virtual computers that can be easily managed and scaled up or down as needed.
  
* Use Amazon RDS for MySQL to handle the database. It's like having a team of experts manage and maintain your database for you, ensuring it's always available and backed up.



 2. Data Analytics Architecture:

# Data Migration:
Connect the existing on-premises MySQL database to AWS using AWS DMS for smooth data migration.

# Data Storage and Processing:

* Store raw and processed data on Amazon S3, providing a scalable and reliable storage solution.

* Launch an EMR cluster using Amazon EMR to process large amounts of data efficiently with tools like Apache Hadoop and Spark.

* Utilize Amazon QuickSight to create interactive visualizations and dashboards based on the analyzed data, making it easier to understand and derive insights.





<p align="center">
Amazon Web Services (AWS)   <br/>
 <img src="https://imgur.com/Bi4YS8U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



# Explanation:

* Storing website files on Amazon S3 ensures they are always available and can be delivered quickly to users worldwide via CloudFront.
  
* Using ALB and EC2 ensures the website remains accessible and responsive, even during high traffic or server failures.
  
* Amazon RDS simplifies database management tasks and ensures high availability and reliability.
  
* For data analysis, AWS services like DMS, S3, EMR, and QuickSight are used to migrate, store, process, and visualize data efficiently and effectively.

In essence, the project involves using various AWS services to create a highly available, scalable, and fault-tolerant architecture for hosting both the application and data analysis workloads in the cloud.






