# Create My First DockerFile

This project contains a simple Dockerfile.

## Details
- Base image: alpine:latest
- Prints: Hello, Captain!

## Run Instructions

### ✅ STEP 1: Open Your GitHub Repo in VS Code
If repo already cloned

Open VS Code

Click File → Open Folder

Select your project folder
👉 ``Basic-Dockerfile``

Click Open

### ✅ STEP 2: Create Dockerfile in VS Code 

📌 Must be:
Name exactly: Dockerfile

No .txt, no extension

In root folder

### ✅ STEP 3: Write Dockerfile Content

Open Dockerfile and paste this:

``FROM alpine:latest
CMD ["echo", "Hello, Captain!"]``

### ✅ STEP 4: Save the File

Press:

`Ctrl + S`

### ✅ STEP 5: To Run your DockerFile

Open the Terminal in your VS code

-Firstly, assign a name to your dockerfile :
`` docker build -t [YOUR DOCKER FILE NAME] .``

Here `t` represents to create new name and `.` dot at the last represent the location.

--Secondly, To run the Dockerfile:
In terminal enter this command:

``docker run [YOUR DOCKERFILE NAME]``


PROJECT URL:

https://roadmap.sh/projects/basic-dockerfile

OUTPUT:

<img width="1072" height="141" alt="image" src="https://github.com/user-attachments/assets/28a1fd9b-b79a-4712-ae03-8e60e747e869" />

