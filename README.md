# BCC-Git-Github-DS

Hello fellow BCC interns and aspiring developers! 

This BCC Git & GitHub Tutorial repository is your friendly guide to mastering version control with Git and collaborating efficiently using GitHub. Here, you'll learn fundamental concepts such as repositories, branches, commits, merges, pull requests, and more to build a solid foundation for managing code collaboratively.

## Windows

Good Luck if you are using Windows (hehehe just move to linux ) 

## Linux
### Installation
1. Before using Git, you need to install it on your system. Open terminal and Follow the steps below to install Git on a Debian-based system (e.g., Ubuntu):
```bash
sudo apt get-update  # Update package lists  
sudo apt install git  # Install Git
```
2. Check Version
```bash
git --version
```
### Basic Git Setup
1. Set Up Your Name and Email
```bash
git config --global user.name "Your Name" #Fill with your name (U can use your username github)
git config --global user.email "your.email@example.com" #Fill with your gmail
git config --global --list #Check your list
```
2.Initialize a Git Repository
```bash
mkdir test-ds-git #make a file
cd test-ds-git  
git init 
git status #Check if you successfully initialized a Git repository
```
Possible Output:

  On branch master

  No commits yet

  nothing to commit (create/copy files and use "git add" to track)

3. Create and Commit a File
```bash
echo "World Hello" > hello.txt  # Create a new file named hello.txt  
git add hello.txt  # Stage the file to be included in the next commit  
git commit -m "First commit"  # Save the changes with a meaningful commit message
```
Possible Output:
[master (root-commit) 213883c] First commit

 1 file changed, 1 insertion(+)
 
 create mode 100644 hello.txt


### Basic Github
1. Create Repository
   - Go to GitHub and log in.
   - Click New Repository -> Enter a repository name -> Choose Public or Private -> Click Create repository.
<p align="center">
  <img width="100%" src="pic/S1.png" alt="pic1">
</p>

You can choose between 

2. Clone an Existing Repository
```bash
cd
mkdir ds-github
cd ds-github
git clone https://github.com/your-username/your-repo-name.git  
cd your-repo-name
```
2. Use the Token for Git Authentication
```bash
git remote set-url origin https://YOUR_GITHUB_USERNAME:TOKEN@github.com/YOUR_GITHUB_USERNAME/YOUR_REPO.git
```
3. Make Changes and Push to GitHub
```bash
touch test.py
git add .  # Stage all changes  or u can use git add test.py
git status # You can see the changes
git commit -m "Add file test.py"
```













