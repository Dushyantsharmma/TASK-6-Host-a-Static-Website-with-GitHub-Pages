# TASK-6-Host-a-Static-Website-with-GitHub-Pages

## Objective:
- Deploy a simple HTML (static) website using GitHub Pages.

## Tools Required:
- GitHub Pages

## Deliverables:
- App link: https://github.com/Dushyantsharmma/TASK-6-Host-a-Static-Website-with-GitHub-Pages
- Repo link: https://dushyantsharmma.github.io/TASK-6-Host-a-Static-Website-with-GitHub-Pages/

---

## Folder Structure:
website-folder/
- ├── index.html
- ├── CSS/
- │   ├── all.min.css
- │   ├── bootstrap.min.css
- │   └── Style.css
- └── images/
-    └── bg-masthead.jpg
  


## Step 2: Initialize Git and Push to GitHub

Follow this cmds:
- git init
- git add .
- git commit -m "initial commit"
- git branch -M main
- git remote add origin https://github.com//my-static-site.git
- git push -u origin main
![image](C:\Users\227du\OneDrive\Pictures\Screenshots)

# After files are pushed into github repo automatically action will work and complete the Build ---> report build status ---> deploy

![image](https://github.com/user-attachments/assets/e5593b10-f435-4caa-90fd-17cb44c53b77)


## Step 3: Enable GitHub Pages
    > Enable GitHub Pages:
    - Go to your repo on Github
    - Click setting ----> pages
    - Under source, choose: deploy from a branch
      Branch: main
      Folder: / root
    - Click save
    - GitHub will give you a live website link after a few seconds.

![image](https://github.com/user-attachments/assets/0ecc522c-41f9-48db-ac18-320a93b4834c)

Then finally access the application use for github provided link:
- https://dushyantsharmma.github.io/TASK-6-Host-a-Static-Website-with-GitHub-Pages/

