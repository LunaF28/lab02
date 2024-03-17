
# Lab 02 - Intro to GitHub

## Timeline
<table>
  <thead>
      <td style="text-align:left;">Assigned</td>
      <td style="text-align:left;">Monday 9 September 2024</td>
  </thead>
  <tfoot>
      <td style="text-align:left; color: red;">Deadline</td>
      <td style="text-align:left;">Friday 13 September 2024</td>
  </tfoot>
</table>

![Lab 2 Assignment](https://github.com/allegheny-college-cmpsc-104-Fall-2024/lab02/blob/main/github-mark2.png)

## Project Goals
- Deepen understanding of GitHub's collaboration features.
- Explore pull and push operations.
- Work on branches on GitHub.
- Demonstrate the GitHub Flow.
- Enhance skills for collaborating effectively on projects using GitHub.

## Tools
- A computer
- Internet connection for installation and documentation reference
- A GitHub account

## Learning Outcomes
These assignment learning outcomes contribute to the following course learning outcomes described in the course syllabus:

1. Describe and explain processes such as software installation or design for a variety of technical and non-technical audiences ranging from inexperienced to expert.
2. Use professional-grade integrated development environments (IDEs), command-line tools, and version control systems to compose, edit, and deploy well-structured, web-ready documents and industry-standard documentation tools.

## Instructions

### Part 1: Clone the Repository and Read the README.md File 
1. Click on the assignment link and accept the assignment.
2. Use the `git clone` command followed by your repository's URL. (Find this URL on your GitHub repository page under the "Code" button.)

### Part 2: Creare a New Branch: 
1. Delete the "TODO" here.
2. Create a new branch named "update_readme".
3. Push this new branch to the GitHub repository.

### Part 3: Explore Pull and Push Operations: 
1. Delete _**"This is a typo"**_ here.
2. Open a pull request for your branch with the commecnt "Delete a typo."
3. Merge your pull request.

### Part 4: Git Commands
- Please complete the TODOs in `writing/git_command.md`.

### Part 5: Write about GitHub Collaboration
- In `writing/reflection.md`:
    - Discuss how the pull and push mechanisms in GitHub are fundamental to the functionality of distributed version control systems.
    - Share your insights and personal experiences with utilizing GitHub branches
    - Explain What is GitHub Flow? Provide a thorough analysis beyond its basic definition, focusing on the importance of each GitHub Flow step and its impact on collaborative software development.

### _Notes_: 
- Make sure to put your assignments in a folder named after your course. After you upload them to GitHub, your work is saved and you can get to it anytime.
- Within `writing/git_command.md` and `writing/reflection.md`, you will find several TODOs awaiting your completion. As you work, please ensure to remove all TODO markers. 
- For this lab, GatorGrader will verify that all TODOs have been eliminated and that your submission includes a minimum of 300 words.

## Resources
- Git Documentation: https://git-scm.com/doc
    - Pro Git book: https://git-scm.com/book/en/v2
- Coursera: https://www.coursera.org/learn/introduction-git-github

## Deliverables
Please submit your work by pushing it to your GitHub Classroom repository.
- You will modify the files `writing/git_command.md` and `writing/reflection.md` to respond questions in the document.

## Project Assessment
- **Completion of Steps 2 and 3 (20%)**: Successfully completing Steps 2 and 3 will each contribute 20% towards the assessment
- **Report Quality (40%)**: The quality of the writing in `writing/reflection.md` will be assessed, focusing on clarity, structure, and adherence to the assignment guidelines.
- **Git Command Proficiency (30%)**: Correctly answer questions related to Git commands in `writing/git_command.md`.
- **Achieve GatorGrader Compliance (10%)**: Successfully meets the criteria set by GatorGrader.

## Gator Grade
### GatorGrade Checks for Immediate Feedback

To provide immediate feedback on your submissions, we're utilizing GatorGrade. Upon submission, if there's a thick red X, it indicates missing components. This X will turn into a green check mark once your submission is complete. For details on what's missing, click on the red X.

To meet the lab assignment's baseline writing and commit requirements, you can use the department's `GatorGrade` tool. Ensure Python3 is installed on your computer (check with `python --version`). If Python is not installed, please follow these guides:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [Setting Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Installing `GatorGrade`:

- [Install](https://pipx.pypa.io/stable/) [pipx](https://pipx.pypa.io/stable/) if you haven't already (`pip install pipx`).
- Install `GatorGrade` using pipx (`pipx install gatorgrade`).
- Running `GatorGrade`:
 `gatorgrade --config config/gatorgrade.yml`

Good luck!
