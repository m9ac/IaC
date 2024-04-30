# IaC

VpcFormation:

Once you have AWS CLI tools installed and configured, entering the following command will spin up a pair of peered VPCs with subnets and internet gateways.

aws cloudformation create-stack --stack-name <VPC-stack-name> --template-body file://</path/to/file>/VpcFormation.yml

Deletion is accomplished by running the following command

aws cloudformation delete-stack --stack-name <VPC-stack-name>

As always, feel free to adjust the code on an as-needed basis.

Happy networking!