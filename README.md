GitHub Actions – Initial Setup
1. Install Visual Studio Code

Download and install Visual Studio Code on your laptop.

2. Install Git

Download and install Git on your laptop.

Verify the installation by running:

git --version
3. Sign in to GitHub from VS Code

Open VS Code and sign in to your GitHub account.

Make sure you have access to the GitHub repository you want to work with.

4. Configure Git

Open the Git Terminal in VS Code and run the following commands:

git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"

Replace the name and email with your GitHub account details.

5. Create Your First GitHub Actions Workflow

Create the following folder structure in your repository:

.github/
└── workflows/
    └── first-workflow.yml

Create a YAML file inside the workflows folder.

This will be your first GitHub Actions workflow for testing and learning CI/CD.

Repository Structure
your-repository/
│
├── .github/
│   └── workflows/
│       └── first-workflow.yml
│
└── README.md

You can then commit and push the workflow to GitHub and verify that it appears under the Actions tab.
