#  Cloud Formation High Availability Deployment Template

These are Cloud Formation diagram and template showing how to deploy a web-application for high availability


## How to use it

You will need an AWS account to use it:

* create AWS account
* create an IAM user
* create an IAM role with administrator access (Do this only for testing, in production make sure you use least privilege)
* assign the IAM role to the user you created earlier
* navigate to the folder where the code has been saved
* run the command 'create.sh high-availability-stack high-availability-stack-template.yml high-availability-stack-parameters.json'
* Once the terminal displays a StackId go to the AWS console, open Cloud Formation, select the Northen Virginia and you will see your stack

## What You're Getting
```bash
├── CONTRIBUTING.md
├── README.md - This file.
├── high_availability_diagram.csv # Tabular representation of the infrastructure diagram data
├── high_availability_diagram.png # Diagram of the high availabiliy infrastructure deployed by the Cloud Formation template script
├── create.sh # Helper script for running the create-stack command
├── update.sh # Helper script for running the update-stack command
├── high_availability_stack.yml # Cloud Formation script deploying the high availability stack
└── high_availability_stack_parameters.json # Paramaters values

```
## Contributing

Do not hesitate to submit a pull request.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
