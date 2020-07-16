This repository contains Packer specification for the AMI used by Terraform

![CircleCI](https://circleci.com/gh/superbounou/livestorm_app.svg?style=svg)

# Usage

```bash
cp env.example .env
# edit your credentials
source .env
packer build nginx.json
```