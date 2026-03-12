# AWS-VPC-Peering-project
Hands-on AWS cloud networking project implementing VPC Peering to establish secure private connectivity between two VPC networks.
# AWS VPC Peering Project

## Overview
This project demonstrates how to connect two Virtual Private Clouds (VPCs) in AWS using VPC Peering.

The goal is to enable private or secure communication between EC2 instances located in different VPC networks.

## AWS Services Used
- Amazon VPC
- EC2
- VPC Peering
- Route Tables
- Security Groups

## Architecture
Two VPCs were created with different CIDR ranges.

VPC-1: 10.0.0.0/16  
VPC-2: 192.168.0.0/16

A VPC Peering connection was established to allow communication between the two networks.

## Steps Performed
1. Created VPC-1
2. Created VPC-2
3. Launched EC2 instances in both VPCs
4. Created VPC Peering connection
5. Updated route tables
6. Tested connectivity using ping

## Result
Successfully established private communication between two VPC networks.

## Author
Pranav Thakare
