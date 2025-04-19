# My First Git Project

## Step 1: Install Git
Go to https://git-scm.com/downloads, choose your operating system, and follow the instructions.
To check if it’s installed, open a terminal and type:

<pre>git --version </pre>

You should see something like: git version 2.xx.x

##  Step 2: Create Your Project Folder
Open Git Bash or your terminal, and type:

<pre>mkdir my-first-git-project
cd my-first-git-project </pre>

This creates a new folder and moves you into it. (You may use any name)

## Step 3: Initialize Git
Run this command to make the folder a Git project:

<pre>git init</pre>

This creates a hidden .git folder — that’s where Git tracks all the changes.

## Step 4: Add a File
Create a README file to describe the project:

<pre> echo "# My First Git Project" > README.md </pre>

## Step 5: Save Your Changes (Commit)
First, stage the file:

<pre> git add README.md </pre>

Then commit it (this saves a version in Git):

<pre> git commit -m "Initial commit with README" </pre>

![Screenshot (127)](https://github.com/user-attachments/assets/7df2e6a8-0e51-4a5d-960f-945971ffc9a2)

## Step 6: Create a GitHub Repository

Go to https://github.com

Click + at the top right → New repository

Name it my-first-git-project (I'm keeping the name consistant)

Leave everything else as-is and click Create repository

![Screenshot (128)](https://github.com/user-attachments/assets/65472b11-0f22-4547-b58e-c7a1560d1fab)

## Step 7: Connect GitHub to Your Local Project
GitHub will show you a link. Copy the HTTPS version.

Back in the terminal:

<pre>git remote add origin https://github.com/YOUR_USERNAME/my-first-git-project.git</pre>
In my case i replaced "YOUR_USERNAME" with "sabelo-madi"

## Step 8: Push Your Project Online
Before pushing, rename the branch to 'main' (optional but recommended):

<pre>git branch -M main</pre>

Now push the project to GitHub:

<pre>git push -u origin main</pre>

![Screenshot (129)](https://github.com/user-attachments/assets/591132e8-ff11-4e3d-96b0-b03aa7cbdbff)

##  Step 9: Done!
Go back to GitHub and refresh the page. You’ll see your README file there. We just published our first GitHub project!

![Screenshot (130)](https://github.com/user-attachments/assets/cd1d0c65-d235-4d49-b384-7b86ed1c87f8)

---
## Reflection
Git and GitHub are useful because they help you track changes in your work, collaborate with others, and keep your projects safe and organized. In the real world, whether you're working alone or in a team, they make it easy to manage updates, fix mistakes, and share your work online. It's a simple but powerful way to stay in control of your projects.
