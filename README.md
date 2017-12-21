# aws_stack1
This project is to build an AWS stack environment using AWS CLI and cloud formation templates
the following files make up this project

describe_env.sh # this script creates the necessary environment by describing the necessary stack events like Resourcestatus,          #LogicalresourceID ResourceType and the timestamp
	
ecs_stack_cf.yml # this is an amazon cloudformation template that is provided as the input to build the stack
