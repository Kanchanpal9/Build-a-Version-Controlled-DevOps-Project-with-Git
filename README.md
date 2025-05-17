 Build-a-Version-Controlled-DevOps-Project-with-Git

🎯Objective
Create a DevOps project and manage it using Git and GitHub, following good version control practices.

🔧 Tools You’ll Use
   Git (installed locally)
   GitHub account

1.Install Git
  sudo apt-get install git
  
2. Create a New Project Folder
   mkdir devops-project
   cd devops-project
3. Initialize Git
   git init
   echo "# DevOps Project" > README.md
   git add README.md
   git commit -m "Initial commit with README"
   Create a New Branch (e.g., dev)
   git branch dev
   git checkout -b dev
   ![Screenshot 2025-05-17 124552](https://github.com/user-attachments/assets/fa4baab5-e140-4a41-90ac-ddf8f3ac75a4)

5. Go to GitHub → Create a new repository → Follow instructions to push:
    git remote add origin https://github.com/yourusername/devops-project.git
    git push -u origin dev
6. Creat feature branch
   echo "Hello DevOps!" > hello.txt
   git add hello.txt
   git commit -m "Add hello.txt"
   git push origin feature-hello

8. Create a Pull Request on GitHub
   Go to your repo on GitHub

   Click Pull Requests

   Click New Pull Request

   Choose feature-hello → merge into dev
![Screenshot 2025-05-17 130816](https://github.com/user-attachments/assets/80bb8a94-1199-4d55-8d69-f9dadeaddd5a)

6. Add .gitignore Rules

   *.log
   
node_modules/

.env
8. Commit Your Files
   
git add .
git commit -m "Initial commit with README and .gitignore"

8. Add a Tag (Versioning)
   git tag v2
  git push origin v2
![Screenshot 2025-05-17 132902](https://github.com/user-attachments/assets/4e98b478-5bfa-4b25-9faa-69fa4e920767)

9. Create a docs Folder
   mkdir docs

10. Create task1.md File
    using vim
    
   # Task: Hello File

## What I did:
- Created hello.txt
- Wrote "Hello DevOps!"
- Committed and pushed it

## Status:
✅ Done
