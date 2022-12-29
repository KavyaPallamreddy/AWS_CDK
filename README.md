# Create the app
Step1: mkdir hello-cdk
       cd hello-cdk
# Now initialize the app by using the cdk init command. 
Specify the desired template ("app") and programming language as shown in the following examples:
Step2: cdk init app --language python

#After the app has been created, also enter the following two commands. 
These activate the app's Python virtual environment and install the AWS CDK dependencies.
Step 3: .venv/Scripts/activate
Step 4: python -m pip install -r requirements.txt
