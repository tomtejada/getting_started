#Xcode (and Terminal)
###What is the Terminal?
- The Terminal app on your Mac is a terminal emulator which allows text-based access to the operating system (no mouse needed).This is in contrast to the GUI (graphical user interface), which is what we are all used to seeing when we open our computers (desktop, folders, mouse, dropdown menus, etc.). The Terminal provides a command line interface that allows you to input a number of commands to operate your machine.
###What is Xcode?
- Xcode is an IDE (integrated development environment) on your Mac that supports numerous programming languages, including Ruby, allowing you to code efficiently directly on your personal computer.
- Xcode is made for OS X, but first, we need to install it.

###Let's open our Terminal!
1. Type `command + space bar` and type in "terminal" into the search bar.
![xcode1](http://i.imgur.com/DEtPYLa.png)
2. Press `enter`
3. Yours will likely look different. You should see your Mac OS login username in the top. If you do not see the `~`, type `cd` + `enter`. Also, yours will likely have a `$` rather than a pizza with a black background. All of these colors are all easily changable in the preferences, but we can do that later. 
![xcode2](http://i.imgur.com/0dgtLjo.png)
4. Type `pwd` + `enter` into your terminal. This command stands for "print working directory" and will return your current file path you are woring in. Mine returns `/Users/mtejada` as that is my home directory. 
![xcode3](http://i.imgur.com/0dgtLjo.png)

###Xcode download
1. Before the installation process, type `xcode-select -p` + `enter` into your command line. If this returns a file path for the Xcode application, you are good to go and can ignore the rest of these instructions. Most should be moving on to the next step, though.
2. Type the command `xcode-select --install` + `enter` into your command line. An install popup should appear on your screen. Click `Install`.  
![xcode4](http://i.imgur.com/0dgtLjo.png)  
3. Click `Agree` when the License Agreement appears (feel free to read it...lol)  
![xcode5](http://i.imgur.com/68JCQTz.png)  
4. Your computer will begin downloading the software.  
![xcode6](http://i.imgur.com/tRvdjUS.png)  
5. Click `Done` once the software is installed. You now have Xcode!  
![xcode7](http://i.imgur.com/X8yjDqB.png)  
6. Type `xcode-select -p` + `enter`. This should return the file path of the newly installed Xcode application.  


  
