# Git and Github

You are going to learn how to use git and Github and create a new repo on GitHub and clone it to your device. You will be able to push to it as well

## Instructions

### 0. Link your computer to GitHub by creating an SSH key
In case you didn't create the SSH Key from Github and linked it to your computer, do the following steps
- [Read the SSH-Keygen workshop and implement it](https://warehouse.joincoded.com/workshops/2-git-basics/basic-commands-1/ssh-keygen)


### 1. Create a new git repository on Github.com

- Login to your account on [GitHub](https://github.com)
- Click on the green `New` button. (🎁 Gift: [github.new](https://github.new) is a shortcut website that allows you to quickly create a new repo)
- Name it `HelloGithub` 
- Make sure you select `public`
- Create Repo

### 2. Copy the SSH clone link

Now you own this repo because you created it! you can clone it now
- Click on the green `code` button 
- Select SSH and copy the ssh link. Should look like this

  ![ssh](https://user-images.githubusercontent.com/8784343/133893992-19294504-e5e3-4a0f-a6f7-25459e0a1700.png)


### 3. Clone it form terminal
- Open the terminal app 
- Navigate to the folder you created that includes your development work 
- Clone the repo from the copied url 

  ```sh
  $ git clone git@github.com:{YOUR_ACCOUNT_NAME}/HelloGithub.git
  ```
  
- The repo should be cloned now on your device, enter the cloned folder by writing the command 
  
  ```sh
  $ cd HelloGithub
  ```
  
- In case the didn't work, check step 0 again

  
  
### 4. Start modifying your repo
- Create a new text file in this directory with your name. (e.g. "zainab.txt")
- add and commit the empty text file you just made.
- Open the text file, write something about yourself, and save the file.
- add and commit the text file again.
- Go to GitHub and create a new repository called Git-Task.
- push your local repository to the newly created remote repository.
- Add an image of your favorite food in your local repository. (You can download any image for this from Google if you need to.)
- push your repository again.
