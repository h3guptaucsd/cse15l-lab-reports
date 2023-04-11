# Lab Report 1


### Part 1: Installing Visual Studio Code
(If you use a different integrated development environment similar to Visual Studio code or are unable to install it, you can skip this step and move on to the next Part)

To install Visual Studio Code you want to go to there [website](https://code.visualstudio.com/Download) and download whatever operating system your computer is running on (Windows, Mac, Linux, etc) and install Visual Studio Code. 

Next you want to open up VS code and take a screenshot of what you see. It should look something similar to this:
![Alt text](Images/vscode.png)


### Part 2: Remote Access

If you are on Mac, you can skip this steep. If you are running on Windows, this will be your first step. You will need to install [git](https://gitforwindows.org/). After this you will need to set up your default terminal to git bash in vscode. [Turtorial on how to do that](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994) 

The next step is setting up your cse15l account, so that you can access the server. To do this you want to head over to this [tutorial](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit) on how to do this. However, since this a bit out of date, you will need to go through steps 1-5

Step 6:

Enter the username that you were given and then hit continue. 
![Alt text](Images/s1.png)


![Alt text](Images/s2.png)
After this it will ask you to confirm on your duo mobile and after that it will give you a link to change your password that will be sent to your email. 

![Alt text](Images/s3.png)
Enter any password that you want and make sure that you remember this password since this will be used to access the server



After setting up your account you want to open up your terminal and type ssh USERNAME@ieng6.ucsd.edu. If you were able to set up your account properly it will ask you for your password, which is the same one that you made previously in step 6. And if you did everything correctly, it should loop something like this: 
![Alt text](Images/term.png)

Your almost done! Now you can play around with some commands such as:
* cd ~
* cd
* ls -lat
* ls -a
* ls <directory> where <directory> is /home/linux/ieng6/cs15lsp23/cs15lsp23abc, where the abc is one of the other group members’ username
* cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
* cat /home/linux/ieng6/cs15lsp23/public/hello.txt
  
After you have tried some commands you can exist the server either by pressing control c or just typing exist. 
