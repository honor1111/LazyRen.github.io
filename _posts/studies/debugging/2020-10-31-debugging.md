---
layout: post
title: "Debugging logs"
subtitle: "Debugging logs"
category: studies
tags: Debugging
# image: 
---


# *Python import error*

- Crashed with windows app  
 
> I was suffering from python import error, and found i have another unknown python.
> ![](/assets/img/posts/studies/debugging/md-img-paste-2020-10-31-12-44-32.png)
>
> Type *app exe* at window search, and find __*manage app execution aliases*__.
> ![](/assets/img/posts/studies/debugging/md-img-paste-2020-10-31-12-48-24.png)
> 
> 
> Then, disable Windows python  
> ![](/assets/img/posts/studies/debugging/md-img-paste-2020-10-31-12-49-43.png)
> 
> 
> _Voila_ !   
> ![](/assets/img/posts/studies/debugging/md-img-paste-2020-10-31-12-51-01.png)


<br>
<br>

# *Install Python3 for Ubuntu20.04*

My configuration  
OS : *Windows 10 Home 1909(x64)*  
Windows Terminal : *1.4.3243.0*  
Linux OS : *Ubuntu 20.04 LTS*  

```shell
$ sudo apt update 
$ sudo apt install software-properties-common 
$ sudo add-apt-repository ppa:deadsnakes/ppa 
$ sudo apt update 
$ sudo apt install python3.7 (python3.8, python3.6, ...)
```

<br>
<br>


# *VisualStudio Code in WSL*

My configuration  
OS : *Windows 10 Home 1909(x64)*  
Windows Terminal : *1.4.3243.0*  
Linux OS : *Ubuntu 20.04 LTS*  

*How can i see my ubuntu version?* : __cat /etc/issue__
![ubuntu version](/assets/img/posts/studies/debugging/md-img-paste-2020-11-24-23-34-00.png)


<br>

1. Install VS Code at [here](https://code.visualstudio.com/download)( fit your environment at Main OS. in my case x64 Win 10 )
2. During Installation, make sure *__click `Add to PATH`__*
3. Install *__Remote Development__*. This includes Remote - WSL, SSH.
![Remote-Dev](/assets/img/posts/studies/debugging/md-img-paste-2020-11-24-23-24-05.png)

4. Run below bash commands
```bash
# bash
$ sudo apt-get install wget ca-certificates
$ sudo apt-get update
```

<br>


Now, let's open vs code via command-line *`"code ."`*
![vscode-cmd](https://docs.microsoft.com/en-us/windows/wsl/media/wsl-open-vs-code.gif)

Reference : [msdn-link](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-vscode)

<br>


# *No module named pip*

This error literally means __pip module not installed in your PC__. You maybe faced with below cases.
- pip upgrade fail
- very beginning of python setup  

To solve issue, Try install pip module refer to below :

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
```

<br>

# *Ubuntu password setup/change*

```shell
sudo passwd root
"type current password"
"type new password"
"type new password again"
```

<br>

# *Ubuntu add PATH*

```shell
PATH="$PATH:$HOME/hanor2313/.local/bin"
```