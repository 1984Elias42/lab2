# Lab report 2
## 1. StringServer
I write a a web server called StringServer that show string according to the path we type in, and here is my code.\
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/VScode%20screenshot.jpg)
## 2. Remotely Connecting
My computer's system is __windows__, so I installed git on my computer first. If your computer's system is __windows__ just like mine, you will also need to install git on your computer. And here is the download link for git. [Link](https://gitforwindows.org/) \
Then open VScode and press __ctrl__ with __`__ to open the terminal.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%202.png)
Then press __Ctrl__ with __Shift__ with __P__ to Open the command palette and type in _Select Default Profile_.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%207.jpg)
Then select _Git Bash_.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%208.jpg)
Then Click on the __+__ in the terminal window and wait for couple seconds. And you will see something like this.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%206.jpg)
Now we just finished our setup and then we can try to use ssh. Open a terminal in VScode and type in _$ ssh cs15lwi23avn@ieng6.ucsd.edu_ but replace avn with __YOUR ID__.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%2010.jpg)
Then press enter and type in your password. You will see something like this.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%2011.jpg)
## 3. Run Some Commands
Now we can try to run some commands like cd, ls, pwd, mkdir, and cp a few times in different ways.\
Here is the list of some commands to try:\
cd ~\
cd\
ls -lat\
ls -a\
ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc, where the abc is one of the other group members’ username\
cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/\
cat /home/linux/ieng6/cs15lwi23/public/hello.txt\
__Let me show you some results of these commands.__ \
When I type in __pwd__, it will show me the current working directory just like this.\
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%2012.png) \
When I type in __cd perl5__, it will change my current working directory to perl5 and I can use pwd to check if it works. Just like this.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%2013.png)\
When I type in cd ~,it will change my current working directory to home directory and like before, I will use pwd to check if it works.
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%2014.png) \
At the end, let me show you something interesting. I type in __ls /home/linux/ieng6/cs15lwi23/cs15lwi23awg__ to list my classmate's files and folders in his home directory. But it showed __"can not open directory, permission denied."__ It seems that if I want to get access to someone else’s directory, I have to get permission first. \
![Image](https://github.com/1984Elias42/cse15l-lab-reports/blob/main/lab1%2015.png)
