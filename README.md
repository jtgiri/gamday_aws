packer build -var "aws_access_key_id=$AWS_ACCESS_KEY_ID"  -var "aws_secret_key=$AWS_SECRET_ACCESS_KEY" -var "ami=ami-4985b048" -var "ami_name=master"  scripts/packer.json
