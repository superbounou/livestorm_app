This repository contains Packer specification for the AMI used by Terraform

# Usage

```bash
cp env.example .env
# edit your credentials
source .env
packer build nginx.json
```