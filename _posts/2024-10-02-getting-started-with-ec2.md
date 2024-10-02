---
title: "Getting Started with Amazon EC2: A Hands-On Lab Experience"
date: "2024-10-02 09:35:52 +0200"
categories: ["AWS", "EC2"]
tags: ["Amazon EC2", "AWS", "Cloud", "Compute"]
---

## Introduction to Amazon EC2

Amazon Elastic Compute Cloud (EC2) is a powerful web service that provides resizable compute capacity in the cloud, designed to make web-scale cloud computing more accessible for developers. Whether you're a beginner or an experienced user, Amazon EC2 offers flexibility, allowing you to control your computing resources and scale them quickly.

In this lab, I had the chance to explore the fundamental features of Amazon EC2, from launching instances to resizing and managing their configurations.

## Key Objectives of the Lab

During the lab, I learned to:
- Launch a web server with termination and stop protection.
- Monitor an EC2 instance using AWS tools.
- Modify security groups to enable HTTP access to my web server.
- Resize an instance to handle increasing demand and enable stop protection.
- Explore EC2 limits and test stop protection mechanisms.

These tasks helped me become familiar with the essentials of managing EC2 instances effectively in AWS.

## Launching and Configuring an EC2 Instance

The first task was to launch an Amazon EC2 instance with termination and stop protection enabled. Termination protection prevents accidental deletion of the instance, while stop protection ensures that the instance isn't accidentally stopped. I also configured the instance to deploy a simple web server using a User Data script. This script automated the installation and configuration of an Apache server.

Once the instance was running, I assigned it a **Name tag** for easier identification in the AWS Management Console.

## Monitoring Your EC2 Instance

Monitoring is critical for maintaining the health of your EC2 instances. I explored Amazon CloudWatch metrics to track the performance and health of my instance. Through status checks and logs, I could monitor system reachability and detect any potential issues with my instance.

Additionally, the lab introduced me to the **System Log** feature, which is helpful for diagnosing issues related to instance startup and configuration.

## Modifying Security Groups for Web Access

To access the web server I launched, I needed to modify the **Security Group** attached to the EC2 instance. By allowing inbound traffic on **port 80** (HTTP), I was able to successfully connect to my instance's web server and display a custom webpage I had created using the User Data script.

## Resizing the Instance for Scalability

In a real-world environment, the demands on your EC2 instances may change over time. I tested resizing the instance from a t2.micro to a t2.small to handle more workload. I also resized the storage by increasing the EBS volume size from 8 GiB to 10 GiB, showcasing the flexibility of Amazon EC2 in adapting to evolving requirements.

## Conclusion

This hands-on lab was a great introduction to managing, monitoring, and scaling Amazon EC2 instances. From securing web servers with **Security Groups** to resizing instances for improved performance, the lab covered the essential skills needed to use Amazon EC2 effectively. For those starting with AWS, EC2 provides a solid foundation for cloud computing.

If you're ready to dive deeper into Amazon EC2, check out the following resources:
- [Amazon EC2 Overview](https://aws.amazon.com/ec2/)
- [Amazon EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/)
- [Amazon EC2 Monitoring with CloudWatch](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/monitoring-system-instance-status-check.html)
