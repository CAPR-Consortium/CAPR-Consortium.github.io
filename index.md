
The dataWizardry repository is where you will find cleaning scripts for CAPR: https://github.com/CAPR-Consortium/dataWizardry.

To get started working with a repository, you will first need to clone it. Cloning copies a repository to your local machine.

Navigate to the repository you want to clone. Click on the green button titled "code" and copy the SSH link. From the command line, you will navigate to the
directory where you want the repository to exist. For the dataWizardry repository, run this line: <code>git clone git@github.com:CAPR-Consortium/dataWizardry.git</code>.

Initialize all submodules and point to main branch: <code> git submodule update --init --recursive --remote </code>

### Pulling Instructions

Before doing any work, pull using the following commands.

<code>git pull</code>          Before editing any script, pull the latest changes from the root and then from each submodule by changing directory into each submodule.

<code>cd clean</code> or <code>cd api</code>          From the root, you can change directory into submodules.

After saving your edits, you will push changes to the repository.

<code>git add *</code>         Prepares content (your local edits) staged for the next commit.

<code>git commit -m "message about changes you made"</code>          Commits the staged snapshot with a message about the changes you have made so that collaborators can understand your modifications/additions to the repository.

<code>git push</code>          Uploads your local changes.

Other useful commands:

<code>git status</code>          Displays the current state of the working directory and staging area.

<code>git log</code>         Displays commit history.

<code>git checkout main</code>      If you have issues with a detached head, do this.
