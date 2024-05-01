## How to download Visual Studio Code on iMac Desktop? | How to download VS Code on Mac Book pro Laptops?

Visual Studio Code can be installed on any desktops. Find steps for installing in Macbook pro Laptop or Desktop.

VS Code Installation Steps:

1. Go to https://code.visualstudio.com/download



 Click on Download.

2. After the VSCode zip file is downloaded, it will be installed automatically

You may see Visual Studio Code installed.


3. Click on Visual Studio Code icon. Now Click on Open





4. Once opened, you will see Visual Studio Code like below:




## How to configure VS Code to integrate with GitHub | Working with GitHub in VS Code | GitHub Visual Studio Code Integration

GitHub is popular Git based SCM, hosted on cloud for storing and sharing code amongst developers. Using GitHub with Visual Studio Code lets you share your source code and collaborate with other developers right within your editor. 




There are many ways to integrate with GitHub, using the website or using Git client(CLI) or using VS Code as well. We will be learning how to integrate with GitHub from VS Code. Git Support is provided out-of-the-box in VS Code.

Pre-requisites:

GitHub.com account created

Git client is installed on your local machine

VS Code installed

Make sure Git is Enabled in Visual Studio Code

Let's make sure Git is Enabled in VS Code. Click on Manage Icon in the bottom left in VS Code. Click on Settings. 



Search for Git:Enabled make sure Git: Enabled is checked.



Steps to integrate with GitHub from Visual Studio Code

1. Open VS Code, Click on Git icon as Git support is provided out of the box in Visual Studio Code.




2. Click on clone repository, 



3. Click on clone from GitHub


4. Now Click on Allow to sign in using GitHub




5. Enter GitHub Credentials


Click on Authorize Visual Studio code





6. Now Click on Open Visual studio code




7. Choose the location where you like to clone the repo:





8. Now click on Open to open the cloned repository.



How to make code changes in VS Code after cloning?
Open Terminal window in VS Code

Set user Name and Email before you push code changes:

Set your username: 
```
git config --global user.name " First Name Last Name"
```

Set your email address: 
```
git config --global user.email "your@email.com"
```

View the entries:
```
git config --global --list
```

It should print your entries.

Now let's make some code changes, click on Explorer Icon.



Make code changes. 
Save the changes. After saving, click on Git Icon on left to see the list of files modified. You will also notice M that says modified files.



Now you can enter commit message above Commit button and Click on Commit. 


Now click on Yes to stage all your changes.



Now to push your code changes into GitHub
Click on ... under Source Control and select Push


Now you can go into GitHub and see your code changes.
