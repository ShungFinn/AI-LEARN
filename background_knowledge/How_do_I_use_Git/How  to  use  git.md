***This part would tell u :***

# How  to  use  git  ???

#### 1. Download it:

​	The official site is :

​	[Git (git-scm.com)](https://git-scm.com/)

​	U need to do these things follow to download it :

##### 		1.Visit the website of Git.

​			![image-20230722002927374](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722002927374.png)

##### 		2.Click the Downloads icon on the main page.

​			![image-20230722002953656](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722002953656.png)

##### 		3.Just chose the Release which fit your operating system.

​			![image-20230722003031928](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722003031928.png)	

##### 		4.Chose a release version to download.

​			![image-20230722003243821](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722003243821.png)



#### 2.Install it:

​	With process above we can get a install fill for git ,click it to run it(I'd show u in windows x64 system, 'cause mine is that)":

![image-20230722003908167](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722003908167.png)



##### 	1.Read the policy (I don't expect anyone should read it through all ,any way),then click "Next" on the button of the window.

![image-20230722004211222](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722004211222.png)

##### 	2.Chose somewhere to install it (for me , I won't allow anything install in my system disk ),and of bloody course "Next".

![image-20230722004817308](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722004817308.png)

##### 	3.If U have some preference tick on them, and "Next".

![image-20230722005108049](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722005108049.png)

#####  	4.Choose the place to put the short cut ,for most of the situation "Next".

​																														![image-20230722005344188](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722005344188.png)	

##### 	5.Choose the default editor for Git(I won't choose vim if I was U, U even need a guidance for install Git, vim ...), "Next"  BTW.

​																			![image-20230722010009751](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722010009751.png)

​							*here comes the joke that goes 'how do I exit vim' is always the most long-live question in stackoverflow*

##### 		6.U know what I am gonna say : "Next".

​																			![image-20230722010526800](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722010526800.png)			

##### 		7.As someone who is reading the guidance , U should trust me and choose "Use Git from Git Bash only","Next".

​																			![image-20230722010825823](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722010825823.png)			

##### 		8.Hostly IDK what's the difference between , just "Next" is fine.

​																			![image-20230722011140818](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722011140818.png)			

##### 		9.A lot of "Next".

​																															![image-20230722005344188](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722005344188.png)				

##### 		10.Wait until U can click "Finish", and U should click it .

​																			![image-20230722011445373](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722011445373.png)				

#### 3.Use it:

​	That's the essential part.(Also operate in Windows 11 env)

##### 		1.Find & Open "Git Bash", and u can also use right click to open it.

![image-20230722012525360](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722012525360.png)

##### 		2.And here we go!!!

```
// generic command:
    // to choose operte location :
    $ cd <location>
    // for example if u wanna find a file in g disk:
    $ cd g:
    //and if u don't remember the file name vrey clear, using command below to show dir:
    $ ls
    // let's suppose u wanna make a new folder in current location:
    $ mkdir <name>
    // too empty ,hum? to add some content just use "touch" command:
    $ touch <name(with its suffix)>
    // if u wanna exit the floder to the upper folder:
    $ cd ..
    // if u wanna delete 
    $ rm <a content>
    $ rm -m <a folder(need to quit the folder frist)>

// git commands:
    // and we need to set up something while frist usage:
        // to tell git who u are and your email (just tell it, it won't apply for anything but a text):
        $ gitconfig --global user.name "<name>"
        $ gitconfig --global user.email "<email>"
        // and initialize the folder:
        $ git init
```

##### 		3.Local SSH set up

```
// SSH set up
    // we need to make sure  whether u own SSH or not:
    $ ~/.ssh
    // if shows "No such file or directory"(this means if u get a file location you just skip this step):
    	// to make a ssh key in side of ur PC:
    	$ ssh-keygen -t rsa -C "<email>"
    	// it will ask u for the saving location and password just input nothing but press "enter", till it shows a graph about the key
    	// then type the frist command to find where it is:
    	$ ~/.ssh
```

##### 		4.SSH add(we 'd make it in github and other platforms should be ex-bloody-actly the same):

###### 1.go to [GitHub](https://github.com/) (if u don't even own a account , sign up !!!)

###### 2.click ur pic on the right-side-top

 ![image-20230722030809326](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722030809326.png)

###### 3.enter in Settings

###### 4.SSH and GPG keys

![image-20230722030946502](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722030946502.png)

###### 5.new SSH key

![image-20230722031042509](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722031042509.png)

######  6.give any title u like and find the key in folder .ssh (in case of anything you can find it by using `$ ~/.ssh`in git bash), and open the id_rsa.pub (usually the lower one ) with text book,and copy them to fill the Key blank and Add SSH Key

![image-20230722031629825](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722031629825.png)

###### 7.it would ask u to re-type password to confirm operation, just confirm it



#### 4.Relate local to remote

######  1.get ur SSH connecting URL(if u don't have a repository ,make one)

![(image-20230722032451295)](https://github.com/ShungFinn/AI-LEARN/blob/main/background_knowledge/How_do_I_use_Git/pic for md/image-20230722032451295.png)

```
// to make a remote repository:
$ git remote add <repo-name(name it urself)> <url>
// if u wanna check :
$ git remote -v 
```

###### 2.push files

```
// to upload the changes a brif way that is:
$ git add -A
// if u wanna upload with some commit:
$ git commit -m "<commit>"
// and we need to push it to the remote repository:
$ git push <repo-name> <branch(which branch in ur github repository u wanna push)>
```

###### 3.pull files

```
// to down load changes in case some other owner changed remote=repository:
$ git pull <repo-name>
```

###### 4.clone files

```
$ git clone <SSH_url or http_url>
```



# HAVE FUN!!!

# ***<u>By :ShungFinn</u>***