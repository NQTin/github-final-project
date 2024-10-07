# Github Final Project

# Part 1 - GitHub UI
# Scenario

You recently got hired as a developer in a micro-finance startup with a mission to empower and provide opportunities to low income individuals. The core team currently uses Subversion (SVN) for managing code. They want to slowly move their code to Git. You are asked to host their sample code to calculate simple interest on GitHub in a new repository as the first step in this journey. You will not only host the script, but also follow best practices introduced in this course and create supporting documents for the open source project including code of conduct, and contributing guidelines. Additionally, the repository should be available to the community under the Apache License 2.0.

# Objectives
After completing this lab you will have demonstrated that you can:

Create a new repository in your GitHub account. Select an appropriate license for your project. Create main README.md markdown file that explains the purpose of the project. Create Code of Conduct markdown that explains how you want the community to behave and interact with each other. Create Contribution Guidelines markdown that tells the community how to contribute. Commit new file to the repository. Note: Throughout this lab you will be prompted copy and paste URLs into a notepad and save the notepad on your own device. These URLs will be uploaded for peer review in the Final Submission section of the course. You can use any notepad app to keep note of your URLs.

# Task 1: Create a Github Repository
Create a new GitHub repository called "github-final-project" and make sure that it is public.

Select the Add a README file and Choose a license check boxes. Pick Apache 2.0 License from the drop down.

Click Create repository. Your repository is created and includes the README and LICENSE files. Now you are ready to update your repository files to include useful information for your community.

Save the URL of the repository in a notepad to submit later for peer review.

# Task 2: Add a license file
As part of Task 1, you picked a licence when creating the repository. Open the LICENSE.md file and save the URL in a notepad to submit later for peer review.

# Task 3: Update the README file
Add the following information to the file:
```python
A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r
```

# Task 4: Add a code of conduct
A code of conduct helps set ground rules for the behavior of your project’s participants. It defines standards for how to engage in a community.

GitHub provides templates for common codes of conduct to help you quickly add one to your project.

Click the Choose a code of conduct template button. On the left side of the page, multiple codes of conduct are listed.

Click "Contributor Covenant" and then click Review and submit to add the file to your project.

Scroll to the bottom of the page. Ensure that the radio button to commit directly to the main branch is selected and click Commit new file. Your project now contains a code of conduct.

# Task 5: Add contribution guidelines
The contribution guidelines tell project participants how to contribute to the project. To add contributions guidelines, complete the following steps:

1. Create a new file named ```**CONTRIBUTING.md**``` in the root directory of the repository with the following information:
``` All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome. ```
2. Commit the file into the main branch and check if it is listed on the homepage of the repository.

# Task 6: Host the script file
1. Create a new file named simple-interest.sh in the root directory of the repository.

2. Add the following code in the new file:
   ```python
   #!/bin/bash
   # This script calculates simple interest given principal,
   # annual rate of interest and time period in years.
   
   # Do not use this in production. Sample purpose only.
   
   # Author: Upkar Lidder (IBM)
   # Additional Authors:
   # <your GitHub username>
   
   # Input:
   # p, principal amount
   # t, time period in years
   # r, annual rate of interest
   
   # Output:
   # simple interest = p*t*r
   
   echo "Enter the principal:"
   read p
   echo "Enter rate of interest per year:"
   read r
   echo "Enter time period in years:"
   read t
   
   s=`expr $p \* $t \* $r / 100`
   echo "The simple interest is: "
   echo $s
   ```
3. Commit the file into the main branch.

# Author(s): Upkar Lidder
