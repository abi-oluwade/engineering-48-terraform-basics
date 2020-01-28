# Terraform Basics

In our stack we have:
- Terraform = orchestration tool that deploys the image into cloud (for example ec2 instance) and setups up infrastructure, so has the image and does the networking as well
- Chef = configuration management tool and sets up the machine to provision
- Packer = creates an immutable image of that machine
