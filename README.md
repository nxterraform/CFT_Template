In this repo, you will find a sample CloudFormation template and a step-by-step guide to upgrade infrastructure over the fly without interruption with ‘change set’ and ‘value update’ principles provided by AWS. 

# change-set-cft

In this repo, you will learn how to create CloudFormation template code with change set principles and implement changes in a running infrastructure stack without interruption.


Steps:-

original stack:-
Step 1: Take resource1.yaml or modify as per your requirements.
Step 2: Create a new stack and upload a template to the stack.
Step 3: Run the stack

Chnage set:-
Step 1: Create a change set in cloudformation.
Step 2: Open the original template and insert a resource.
Step 3: Replace the current template.
Step4:- Submit


How to run the CFT template in cloudformation?
Run Step:-
    1. Go to the AWS Cloud Formarion
    2. Create a Stack
    3. Upload template
    4. Run the stack

[Click here For the change set code](https://github.com/nxterraform/CFT_Template/tree/main/Change_set)
# Value Update

In this repo, you will learn how to create CloudFormation template code with value update principles and implement changes in a running infrastructure stack without interruption.


original stack:-
step1:- Take a values.yaml or you can modify as per your requirment.
Step2:- Create a new stack and upload a template in stack.
Step3:- Run the stack.


Value update:-
step1:- Take a exiting runnig template.
Step2:- changes and take no interruption value as per bellow table.
Step3:- Click on update stack.
Step4:- Take and updated stack and upload in cloudformation.
Step5:- Submit the stack.
 
 
 
Values                    No Interruption   Some Interruption     Replacement

AllocatedStorage              ✔️                 ❌                 ❌
AvailabilityZones             ❌                 ❌                 ✔️
DatabaseName                  ❌                 ❌                 ✔️ 
DBClusterInstanceClass        ✔️                 ❌                 ❌
DeletionProtection            ✔️                 ❌                 ❌



How to run CFT template in cloudformation?
Run Step:-
    1. Go to the AWS Cloud Formarion
    2. Create a Stack
    3. Upload template
    4. Run the stack

[Click here For the value change code](https://github.com/nxterraform/CFT_Template/tree/main/Values_Changes)

