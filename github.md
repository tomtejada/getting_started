#Github
###What is Github?
- Github is a version control system. If you have ever edited a document on Google Drive or another cloud storage software, this is similar to a version control system. 
- The best part about Github is the collaboration. Github makes it easy for you and anyone on your team to add (commit and push) your code to the same repository, or repo and see the changes everyone on your team has made.
- A Github repo (like the one you are on) is a digital directory or storage space where you can access a project and all the files (and every version of those files) that are saved.
- We will use Github extensively to copy (fork), save (commit), and collaborate (branch), at Coder.new so don't be too nervous about all the lingo and commands that come with Github, just know that it let's us work together no matter where we are!

###Let's set up your Github profile (Part 1)
1. Head over to [Github](http://www.github.com)
2. Click the 'sign up' button
![github1](http://i.imgur.com/Lkev2zU.png)
3. Choose a username, email address, and password for your account
![github2](http://i.imgur.com/R7TvVuM.png)
4. Choose the free plan (this is selected by default)
![github3](http://i.imgur.com/GZWxWi4.png)
5. Check your inbox for an email from Github. Verify your email address by selecting the link in the email body.
![github4](http://i.imgur.com/mAdEaAB.png)

####You are officially part of the largest coding community in the world!
###Downloading Github to your local computer (Part 2)
1. Go to http://www.git-scm.com/  
2. CLick `Downloads for Mac`  
![github1](http://i.imgur.com/vHvYtge.png)  
3. Head back to your terminal. Navigate to your home directory by typing `cd` + `enter`.   
4. Type `git --version` + `enter` into your command line. This should return the most recent version of Git (2.6.4)  
![github2](http://i.imgur.com/vgbIOfX.png)  
5. Time to connect and configure your Github account to your Terminal and local Mac computer. This will make it simple to push and pull code from Github to your local computer (aka the one you are currently sitting at).  
6. Type `git config --global color.ui true` + `enter`  
7. Type `git config --global user.name “YOUR USERNAME”` + `enter` into your Terminal (BE SURE TO ENTER YOUR GITHUB USERNAME INSIDE THE DOUBLE QUOTES WHERE IT SAYS YOUR USERNAME)   
8. Type `git config --global user.email “YOUR EMAIL”` + `enter` into your Terminal (BE SURE TO ENTER YOUR EMAIL CONNECTED TO GITHUB  INSIDE THE DOUBLE QUOTES WHERE IT SAYS YOUR EMAIL)  
9. Almost done! The next step is to generate your SSH (Secure SHell) Key. This makes it nearly impossible for someone to hack your account and it much stronger than just your password alone.  
10. Type `ssh-keygen -t rsa -C "YOUR EMAIL"` + `enter` into your Terminal (BE SURE TO ENTER YOUR EMAIL CONNECTED TO GITHUB  INSIDE THE DOUBLE QUOTES WHERE IT SAYS YOUR EMAIL)  
11. The last command should return: `Enter file in which to save the key (/home/demo/.ssh/id_rsa):   ` (Press `enter`)  
![github3](http://i.imgur.com/DDXmlcS.png)  
12. Next, you should be returned: `Enter passphrase (empty for no passphrase):   ` (Leave blank for now, Press `enter`)  
13. Next, it asks to enter the same passphrase again. You should leave blank and press `enter` again.  
14. The entire key generation process looks similar to the following:  
![github4](http://i.imgur.com/lCLRwg9.png)  
15. Next, we want to grab your SSH key and connect it to your Github. Enter the command `cat ~/.ssh/id_rsa.pub` + `enter` into your command line in Temrinal.  
15. Copy (`command + c`) the entire return value that begins with `ssh-rsa` and ends with your email.  
16. In your internet browser, go to https://github.com/settings/ssh
17. Click `Add SSH Key`  
![github5](http://i.imgur.com/MIdiqu9.png)  
18. For the Title, enter the name of your computer (e.g. "Michael's MacBook Air")  
19. For the Key, paste the entire SSH Key you copied from your terminal. If you need this again, repeat step #14 and #15.  
20. Click `Add key`  
![github6](http://i.imgur.com/k44rCtH.png)  
21. You should see your key with the Title you created as well as a combination of letters and numbers (a red rectangle covers mine).  
![github7](http://i.imgur.com/Ou7QSkJ.png)  
22. So close to being done! In your Terminal, enter the command `ssh -T git@github.com` + `enter`  
23. If it asks for a password, enter your Github password.  
24. It will return: `Are you sure you want to continue connecting (yes/no)?  
25. Type `yes` + `enter`  
26. You should receive a return message that says: `Hi "YOUR USERNAME"! You've successfully authenticated, but Github does not provide shell access.`

####ALL DONE (for now) We'll create our first repository at your first coding session!









