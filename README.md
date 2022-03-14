# Git and Github

You are going to learn how to use git and Github by creating a new repo on GitHub and cloning it to your device. You will be able to push to it as well.

## Instructions

### 0. Link your computer to GitHub by creating an SSH key

- [Read the SSH-Keygen workshop and implement it](https://warehouse.joincoded.com/workshops/2-git-basics/basic-commands-1/ssh-keygen)


### 1. Create a new git repository on Github.com

- Login to your account on [GitHub](https://github.com)
- Click on the green `New` button. (🎁 Gift: [github.new](https://github.new) is a shortcut website that allows you to quickly create a new repo)
- Name it `HelloGithub` 
- Make sure you select `public`
- Create the repo

### 2. Clone the Repo to your device

You own this repo because you created it! It's time to clone it!
- Click on the green `code` button 
- Select SSH and copy the ssh link. Should look like this:  

  ![ssh](https://user-images.githubusercontent.com/8784343/133893992-19294504-e5e3-4a0f-a6f7-25459e0a1700.png)
  
- Open the terminal app 
- Navigate to the folder you created that includes your development work 
- Clone the repo from the copied url 

  ```sh
  $ git clone git@github.com:{YOUR_ACCOUNT_NAME}/HelloGithub.git
  ```
  > ⚠️ If you get an error, check step 0 again
  
- The repo should be cloned now on your device. Go to the cloned repo by writing the command 
  
  ```sh
  $ cd HelloGithub
  ```
  
<!-- ### 3. Edit your repo

- Create a new text file in this directory with your name. (e.g. "zainab.txt")
- `add` and `commit` the empty text file you just made.
- Open the text file, write something about yourself, and save the file.
- `add` and `commit` the text file again.
- `push` your local changes to the remote repository.
- Add an image of your favorite food in your local repository. (You can download any image for this from Google if you need to.)
- `add`, `commit`, `push` your changes. -->

### 3. Make Changes

- Create a new file using `touch` called `greetings.txt`.
- Inside the fle, Write a greeting message.
- Git add, commit and push your changes
