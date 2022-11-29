# AWS--Build-a-WordPress-Website
Building a WordPress Website in AWS

Projects on AWS:
Build a WordPress Website
Deploy and host a production-ready WordPress website on AWS
Get Started with the Implementation Guide
5 Steps  |  60 Minutes


Main
Services Used and Costs
FAQs
In this project, you will learn how to deploy and host WordPress, an open-source blogging tool and content management system (CMS) based on PHP and MySQL. You will implement an architecture to host WordPress for a production workload with minimal management responsibilities required from you. To accomplish this, you will use AWS Elastic Beanstalk and Amazon Relational Database Service (RDS). Once you upload the WordPress files, Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. Amazon RDS provides cost-efficient and resizable capacity, while managing time-consuming database administration tasks for you.

Get Started with the Implementation Guide
What you'll accomplish:

Launch a web stack to host your WordPress application using AWS Elastic Beanstalk and Amazon Relational Database Service (RDS). Elastic Beanstalk provisions and manages the underlying infrastructure (e.g., Amazon EC2 instances) and stack components (e.g., OS, web server, language/framework) for you. RDS provides the MySQL database.

Deploy WordPress using AWS Elastic Beanstalk. You’ll upload the code to Elastic Beanstalk, which handles all deployment details for you.

What you'll need before starting:
An AWS Account: You will need an AWS account to begin provisioning resources to host WordPress. Sign up for AWS.

Skill level: Prior experience with WordPress is required.

AWS Experience: Intermediate familiarity with AWS and its services is recommended.
Monthly Billing Estimate:
The total cost of building a WordPress website will vary depending on your usage and the instance types you select for the web server and database instance. Using the default configuration recommended in this guide, it will typically cost $450/month to host the WordPress site. This cost reflects the minimum resources recommended for a production ready WordPress workload, with only one active web server and a separate Amazon RDS MySQL database instance. The total cost may increase if you use Auto Scaling to increase the number of web server instances in the event of increased traffic to your WordPress site (approximately $75/month for each additional web server assuming that the web server is active for the entire month). To see a breakdown of the services used and their associated costs, see Services Used and Costs.

Additional Resources
Getting Started Resource Center

Need more resources to get started with AWS? Visit the Getting Started Resource Center to learn more.

Whitepaper: Deploying WordPress with AWS Elastic Beanstalk

This whitepaper describes a more thorough implementation of WordPress using AWS Elastic Beanstalk. It includes instructions on setting up a CDN and in-memory caching for your WordPress deployment using Amazon CloudFront and Amazon ElastiCache.

WordPress on the AWS Marketplace

Find and launch pre-configured images running WordPress from the AWS Marketplace.
WordPress Websites on Amazon Lightsail

Accelerate your Wordpress website with Lightsail. It provides everything you need to jumpstart your website on AWS—compute, storage, and networking—for a low, 
