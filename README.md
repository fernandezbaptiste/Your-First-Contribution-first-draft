# Your-First-Contribution

Hey you! Welcome to this repository which marks your start in the Open Source World!! 🌐👯‍♀️

In the next 10 min you will contribute to your first Open Source projects - how crazyyy is that 🚀

To fully understand what the below steps do we essentially want to :

1. Make a copy of this project 
2. Open the project in your local computer
3. We want to add your name into one of the project files ( this will be your contribution to the project 🔥 )
4. Save it
5. Send the updated project with your name to Github

That's what you will be doing, and believe it or not, but that will be your first contribution. 
I know right? Sounds much less scary than you imagined right? 

This is a valid contribution and it will teach you the mechanics of github so you are ready for your second contribution! 

You ready?? Let's do it - we got this ☕️🫶


## 1. Fork the project

"Forking" is done with the fork button.
Fork means will create a copy of this repository in your github account 💪

[screen shot] 

Now that you have the copy on your account, lets bring the entire project on your local computer!

## 2. Clone the repository

clone this repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command:

git clone "url you just copied"
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

[screen shot] 

copy URL to clipboard

For example:

git clone git@github.com:this-is-you/first-contributions.git
where this-is-you is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

Create a branch
Change to the repository directory on your computer (if you are not already there):

cd first-contributions
Now create a branch using the git switch command:

git switch -c your-new-branch-name
For example:

git switch -c add-alonzo-church
Make necessary changes and commit those changes
Now open Contributors.md file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

git status

If you go to the project directory and execute the command git status, you'll see there are changes.

Add those changes to the branch you just created using the git add command:

git add Contributors.md
Now commit those changes using the git commit command:

git commit -m "Add your-name to Contributors list"
replacing your-name with your name.

Push changes to GitHub
Push your changes using the command git push:

git push -u origin your-branch-name
replacing your-branch-name with the name of the branch you created earlier.

If you get any errors while pushing, click here:
Submit your changes for review
If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

create a pull request

Now submit the pull request.

submit pull request

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

Where to go from here?
Congrats! You just completed the standard fork -> clone -> edit -> pull request workflow that you'll often encounter as a contributor!


Celebrate your contribution and share it with your friends and followers by going to web app.

You could join our slack team if you need any help or have any questions. Join slack team.

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out the list of projects in the web app.
