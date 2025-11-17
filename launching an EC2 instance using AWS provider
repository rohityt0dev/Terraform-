terraform {
  required_providers {
    aws = {
      source = "hashicorp/aws"
      version = "6.21.0"
    }
  }
}

provider "aws" {
  region = "ap-south-1"
}

resource "aws_instance" "e1" {
    ami = "ami-03695d52f0d883f65"
    instance_type = "t2.micro"
    tags = {
        Name = "FirstInstance"
    }
}
