# AWS EC2 Instance Setup

This repository contains two scripts for setting up AWS EC2 instances:

- A script to launch an EC2 instance using the AWS CLI.
- A CloudFormation YAML script to create an EC2 instance.

## Prerequisites

- AWS CLI installed and configured with appropriate permissions.
- AWS CloudFormation service permissions.
- An AWS account with access to EC2 and CloudFormation.

## Contents

- `ec2-user-data.sh`: A shell script to launch an EC2 instance using the AWS CLI.
- `0-just-ec2.yaml`: A CloudFormation YAML script to create an EC2 instance.

## Usage

### Script 1: Launch EC2 Instance using AWS CLI

#### Description

The `launch_ec2.sh` script launches an EC2 instance with the specified parameters.

#### Parameters

- `AMI_ID`: The Amazon Machine Image ID to use for the instance.
- `INSTANCE_TYPE`: The type of instance to launch (e.g., `t2.micro`).
- `KEY_PAIR_NAME`: The name of the key pair to use for the instance.
