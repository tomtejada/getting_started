#Ruby (RVM)
###What is Ruby and RVM?
- Ruby is a dynamic and powerful server-side language that lets us build fun applications. It was written to have elegant syntax and be easy to read and write!
- RVM, or Ruby Version Manager, is a command-line tool that lets you work with multiple Ruby environments and open source Ruby code.

###Let's update Ruby 
1. Open Terminal. Remember you can do this by typing `command + space` and searching "terminal", or you can look through your applications folders and click on the Terminal application.
2. Navigate to your root directory by typing `cd` + `enter` into your command line. Hopefully you recall some of this from the previous environment setup tutorials!
3. Enter the following command into your Terminal command line:  
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
4. Once this completes downloading, we need to update your `~/.bash_profile` file. Bash is the shell, or the command line interpreter that takes in these commands we've been typing into our Terminal and helps our operating system carry each command out. Our Bash profile is a hidden file (denoted by the `.` in front of the file name `.bash_profle`) that keeps certain instructions and commands that we don't need to see regularly. 
5. If you type `ls` + `enter` into your command line, you will be returned file names you might be familiar with. Here is an example of what mine looks like:  
![ruby1](http://i.imgur.com/XHCIriy.png)  
6. However, our computer also holds many hidden files that we don't need to see or open regularly. You can find these by typing the command `ls -a` + `enter`. This will return many hidden files as well as your visible files and folders. I recommend keeping those hidden files hidden and to not change them. Except the one we are about to edit.
7. List the hidden files again (`ls -a` + `enter`). Type the command `open .bash_profile` + `enter`. This will open your Bash Profile. 
8. Scroll to the very bottom of your profile and paste the following line into your Bash Profile:  
`[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # Load RVM into a shell session *as a function*`  
9. Save your Bash Profile (`command + s` or `file` > `Save`).
10. Exit our of your Bash Profile. Quit your Terminal application (`command + Q`).
11. Reopen your Terminal Application. 
12. Type `rvm` + `enter`. This should return a list of commands and help. 
13. Type `rvm -v` + `enter`. This should return rvm 1.26.11 (if not, we will update together in the first coding session).  
![ruby2](http://i.imgur.com/2hgd80n.png)  
14. Type `rvm install 2.2.0` + `enter`. This will install the latest version of Ruby, 2.2.0.
15. Type `rvm use 2.2.0` + `enter`. This will tell your Xcode to use this version of Ruby.
16. Type `ruby -v` + `enter`. This should return ruby 2.2.0  
![ruby3](http://i.imgur.com/ihf5taS.png)  

####Congrats! Ruby is installed and our coding environment is ready to go!  
