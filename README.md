# AWS-Challenge

## Overview
---
For this task, I was asked to architect an AWS infrastructure within a custom VPC that runs a flask application connected to an RDS database. Below I will describe what steps I took and my reasons for doing so.

## VPC Creation
---
When creating my custom VPC, I gave it the name, **aws-challenge**, and I assigned it the IPv4 CIDR range 10.0.0.0/16 as this would give the VPC a large range of IP addresses to assign to resources within, like the subnets for example.