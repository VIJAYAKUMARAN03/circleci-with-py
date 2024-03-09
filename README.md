# Running Python code in CircleCI Pipeline

This guide outlines the steps to run Python code in CircleCI.

## Getting Started

Follow the steps below to set up CircleCI and run a pipeline.

### Step 1: Clone the Repository

Clone the repository containing the Terraform code to your local environment and set it as your local repository.

```bash
git clone https://github.com/VIJAYAKUMARAN03/basic-aws-terraform-circleci.git
cd basic-aws-terraform-circleci
```

## Step 2 : Create a New Repository
Create a new repository in your Git hosting service to host your Terraform code.

## Step 3: Set up CircleCI
Create a CircleCI account and connect it with your Git account. Follow the prompts to integrate your repository with CircleCI, which will be shown as a project. 
- Link : https://circleci.com/vcs-authorize/

## Step 4: Configure Environment Variables
Set the requried environment variables in CircleCI for the project.
- Note: Environment variable names are case-sensitive.
- Refer : https://circleci.com/docs/set-environment-variable/

## Step 5: Pull Repository Changes
Pull the changes from your newly created repository.
```bash
git pull origin main
```

## Step 6: Add Files to Your Repository
Add the necessary files from the cloned repository to your newly created repository.
```bash
git add .
```

## Step 7: Commit and Push Changes
Commit your changes and push them to your repository.
```bash
git commit -m "Initial commit with Python files"
git push origin main
```

After pushing changes, monitor the pipeline output in the CircleCI dashboard to ensure successful execution.


## Thanks for reading, Have a nice day!
