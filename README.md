# Create the app

# Step1:
mkdir hello-cdk
# Step2:
cd hello-cdk
       
       
# Now initialize the app by using the cdk init command. 


Specify the desired template ("app") and programming language as shown in the following examples:
# Step3: 
cdk init app --language python

# After the app has been created, also enter the following two commands. 


These activate the app's Python virtual environment and install the AWS CDK dependencies.
# Step4: 
.venv/Scripts/activate
# Step5: 
python -m pip install -r requirements.txt

# At this point you can now synthesize the CloudFormation template for this code.

# Step6:
cdk synth


To add additional dependencies, for example other CDK libraries, just add
them to your `setup.py` file and rerun the `pip install -r requirements.txt`
command.

# Step7:
cdk deploy

## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation
