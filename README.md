# Scalable Web App with ALB and Auto Scaling 

## Overview

This project demonstrates a highly available and scalable web application architecture on AWS.

Traffic is distributed using an Application Load Balancer (ALB), while an Auto Scaling Group automatically launches or terminates EC2 instances based on CPU utilization.

## Services Used

* Amazon EC2
* Application Load Balancer
* Auto Scaling Group
* Security Groups

## Workflow

1. Users access the application through ALB.
2. ALB distributes traffic across EC2 instances.
3. Auto Scaling monitors CPU utilization.
4. Additional EC2 instances are launched automatically during high traffic.
5. Instances are terminated when demand decreases.

## Features

* High Availability
* Load Balancing
* Automatic Scaling
* Fault Tolerance
