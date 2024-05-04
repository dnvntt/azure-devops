# azure-devops
this is a repo for azure devops

This project demonstrate using Makefile to create shortcuts to  build, test, and deploy one project
You need to edit content of these files: requirements.txt, hello.py, test_hello.py, Makefile based on what you want to test

# Create the Python Virtual Environment
python3 -m venv ~/.myrepo
source ~/.myrepo/bin/activate

# Local Test
Run "Make all" on Azure cloud shell to see the result

# CI: Configure GitHub Actions
This guideline to use GitHub Actions to do Continuous Integration 

1. Enable Github Actions
Go to your Github Account and enable Github Actions.

2. Replace yml code
Replace the pythonapp.yml code with the following scaffolding code.

4. Verify Remote Tests pass
Push the changes to GitHub and verify that both lint and test steps pass in your project.
![GitHub Action result](github%20action%203.PNG?raw=true "Optional Title")
