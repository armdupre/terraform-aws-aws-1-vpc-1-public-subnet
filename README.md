# module-1-vpc-1-public-subnet/aws

## Description
Terraform module for Vpc deployment on Amazon Web Services

## Deployment
This module creates a topology with a single virtual private cloud having a single public facing subnet.

## Usage
```tf
module "Vpc" {
	source = "armdupre/module-1-vpc-1-public-subnet/aws"
	InboundIPv4CidrBlock = "1.1.1.1/32"
}
```