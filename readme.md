# Terraform Basics

In our stack we have:
- Terraform = orchestration tool that deploys the image into cloud (for example ec2 instance) and setups up infrastructure(vpc, networking etc), so has the image and does the networking as well
- Chef = configuration management tool and sets up the machine and can provision it (e.g recipes, metadata, berks_cookbook, unit and spec tests, kitchen.yml and more)
- Packer = creates an immutable image of that machine
