# Visual Studio Code Settings Sync

> Type "Sync" In Command Palette in order to download / upload

## Key Features
```
1. Use your github account token.
2. Easy to Upload and Download on one click.
3. Saves all settings and snippets files.
4. Upload Key : Ctrl + Alt + u
5. Download Key : Ctrl + Alt + d
6. Type Sync In Order to View all sync options
```      
    
## Steps To Get the Github Key.

This extension required your GitHub Account Personal Access Token. You can create one simple by looking into the following pictures.
**Goto Settings / Personal Access Tokens / Generate New Token**


![Goto Settings / Personal Access Tokens](http://shanalikhan1.github.io/img/github1.PNG)

**Select Scopes**

![Select Scopes](http://shanalikhan1.github.io/img/github2.PNG)

**Get Unique Key**

![Get Unique Key](http://shanalikhan1.github.io/img/github3.PNG)


> You need to save this key for this extension for future use, and dont share this key with anyone as it will get your data without needing to logg in.


## Upload Your Settings For the first time


**Press Ctrl + Alt + u it will ask your github account access token.**

> Type "Sync" In Command Palette into order download / upload

Enter the github account in the window and click enter.

![github account access token](http://shanalikhan1.github.io/img/upload1.png)

**Upload your settings automatically and give you GIST ID.**
Copy this Gist ID in order to download the settings in other machines.

![uploaded automatically](http://shanalikhan1.github.io/img/upload2.png)


## Download your Settings

**Press Ctrl + Alt + d it will ask your github account access token.**

> Type "Sync" In Command Palette into order download / upload

Enter the github account in the window and click enter.

![github account access token](http://shanalikhan1.github.io/img/upload1.png)

**Enter Your GIST ID.**
you need to enter your Gist ID in order to get the all files

![Enter Your GIST ID](http://shanalikhan1.github.io/img/download2.png)

**Settings Downloaded.**
You are Done ! All your files are downloaded

![Enter Your GIST ID](http://shanalikhan1.github.io/img/download3.png)

# How To Contribute
Download source code and install dependencies

```
git clone https://github.com/shanalikhan1/code-settings-sync.git
cd code-settings-sync
npm install
code .
```
Make the respective code changes.

Go to the debugger in VS Code, choose `Launch Extension` and click run. You can test your changes.

Submit a Pull Request.
   

# Backlog
1. Make it work for Linux or Mac. As I have only tested and made it worked for windows.
2. Extensions Synchronization [ Currently Not Possible ] 
    
# Contributors
[Shan Ali Khan](https://github.com/shanalikhan1)
    
# License
MIT
