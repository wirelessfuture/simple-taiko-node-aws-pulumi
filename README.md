# Simple Taiko Node AWS template with Pulumi
This simple repository allows you to create your own Lightsail instance in AWS with the simple-taiko-node repository and 
docker image pre-pulled. 

---

## What is being deployed?
This pulumi template by default will deploy one medium sized lightsail instance to AWS. This will cost about ~$20 per month on your AWS account. See [pricing](https://aws.amazon.com/lightsail/pricing/) for more info. This lightsail instance will have the minimum specs required to launch a node on Taikos testnet using their simple-taiko-node.

- 4 GB Memory
- 2 Core Processor
- 80 GB SSD Disk
- 4 TB Transfer

---

## Requirements
* AWS Account
* [Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
* [Install Pulumi](https://www.pulumi.com/docs/get-started/install/)
* [Configure your AWS credentials](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html) **(you will need an IAM user that has API access and it needs a policy attachment for Lightsail resources)**

---

