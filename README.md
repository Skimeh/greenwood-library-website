Enhancing a Community Library Website
Welcome to the Community Library Website Enhancement project! This capstone project focuses on improving the library’s website while also learning and practicing essential Git and GitHub workflows. It’s a team effort by Morgan and Jamie, with a focus on collaboration, version control, and conflict resolution.

Project Objectives:

Cloning and Branching

Practice cloning a repository and creating branches for feature development.

Collaboration with Git

Gain hands-on experience in staging, committing, and pushing changes while working together.

Pull Requests and Conflict Resolution
Learn how to create and review Pull Requests (PRs), resolve conflicts, and merge changes into the main branch.

Website Setup in the Main Branch:
Use Visual Studio Code to create the initial files for each web page.



Getting Started
1. First, clone the repository to your local machine:

            git clone https://github.com/skimeh/greenwood-library-website.git
            cd greenwood-library-website

2. Main Branch Setup
     Create Web Page Files
            In the main branch, ensure the following files exist using Visual Studio Code:

            home.html
            about_us.html
            events.html
            contact_us.html
            Collaboration
            Create a Pull Request (PR) on GitHub for your branch.
            Review each other’s changes, resolve any conflicts, and then merge the PR into the main branch.
3. Add Random Content
Stage, Commit, and Push Changes
Stage, commit, and push the changes directly to the main branch:
            git add home.html about_us.html events.html contact_us.html
            git commit -m "Initial setup: Add web page files with placeholder content"
            git push origin main
4. Making Changes
Create a branch for Morgan and Jamie:
            git checkout -b add-book-reviews
            git checkout -b update-events
After making changes, stage and commit them:
            git add add-book-reviews
            git commit -m "Morgan's branch"

            git add update-events
            git commit -m "Jamie's branch"
Push your branch to the remote repository:
            git push origin add-book-reviews
            git push origin update-events

           



           
