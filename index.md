# What is CAPR?
The Computarized Assessment of Psychosis Risk is multi-site study and consortium of six universities dedicated to the understanding and early idenfitication of psychosis in the general population. We are currently developing a battery of tasks, surveys, and clinical instruments that will be used to calculate psychosis risk in the community.

See our 2021 paper in the [Journal of Psychiatry and Brain Science](https://jpbs.hapres.com/htmls/JPBS_1407_Detail.html) for details about the project.

## Affiliated Universities
- Yale University
- Northwestern University
- Temple University
    - Zeeshan Huque: zeeshan.huque@temple.edu
- University of California, Irvine
- University of Georgia
    - Lauren Luther: lauren.luther@uga.edu
- Emory University
- University of Rochester Medical Center
    - Tanya Tran: tanya_tran@urmc.rochester.edu

## What is dataWizardry?
dataWizardry is both a repository and a collective of computer scientists, psychology post-docs, graduate students, and research assistants. We meet once a month to review data-related issues and efforts towards data cleaning. We have developed a data cleaning framework in R to manage the 64 data streams from RedCap, Qualtrics, and MongoDB into a unified API pipeline. Take a look at our [README](https://github.com/CAPR-Consortium/dataWizardry/blob/master/README.md)!

The dataWizardry repository is where you will find cleaning scripts for CAPR: https://github.com/CAPR-Consortium/dataWizardry.

### Mission Statement
>A multisite effort to create a unified, standardized approach to developing cleaning and scoring scripts that handles all CAPR data, works for all sites, and is easily understood by future researchers.

If you want to request data, please contact one of the data deputies listed above in the Affiliated Universities section with the subject line "Data Request - CAPR."


# Getting Started
If you would like to join our team, please first create a GitHub account. Please contact any of the following repository owners with the subject line "Collaboration Request -- CAPR dataWizardry" and share your GitHub username:
- Josh Kenney: joshua.kenney@yale.edu
- Minerva Pappu: minerva.pappu@yale.edu
- Trevor Williams: trevor.williams@northwestern.edu

## After Joining dataWizardry
Once you have received access, please review the [README](https://github.com/CAPR-Consortium/dataWizardry/blob/master/README.md). If you are new to GitHub and Git, see the [quickstart documentation](https://docs.github.com/en/get-started/quickstart). After these steps, request an onboarding meeting from one of the repository owners.


## Working with the dataWizardry repository

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

<code>git commit -m "message about changes you made"</code>          You use a flag "-m" to add a message attached to your commit. Commits the staged snapshot with a message about the changes you have made so that collaborators can understand your modifications/additions to the repository.

<code>git push</code>          Uploads your local changes.

Other useful commands:

<code>git status</code>          Displays the current state of the working directory and staging area.

<code>git log</code>         Displays commit history.

<code>git checkout main</code>      If you have issues with a detached head, do this.
