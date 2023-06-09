# Your-First-Contribution

Hey you! Welcome to this repository which marks your start in the Open Source World!! 🌐👯‍♀️

In the next 10 min you will contribute to your first Open Source projects - how crazyyy is that 🚀

To fully understand what the below steps do, we essentially want to :

1. fork -> 2. clone -> 3. edit -> 4. pull 

In what does that mean in normal language 🙈:

1. Make a copy of this project 
2. Open the project in your local computer
3. We want a couple of things in a file ( this will be your contribution to the project 🔥 ) 
4. Send the updated project with your name to Github

That's what you will be doing, and believe it or not, but that will be your first contribution!
I know right? Sounds much less scary than you imagined right? 

This is will teach you the mechanics of github so you are ready for your next contributions! 

You ready?? Let's do it - we got this ☕️🫶

Requirement: If not already done, download Git [here]([url](https://docs.github.com/en/get-started/quickstart/set-up-git)).

## 1. Fork the project

Start by staring the account and click on the fork button.

Fork means will create a copy of this repository in your own github account. 💪

<img width="1281" alt="Screenshot 2023-05-29 at 11 48 15" src="https://github.com/fernandezbaptiste/Your-First-Contribution/assets/83458751/b059d2f4-dc81-4969-a29f-c8efd42f835e">

Now that you have the copy on your account, lets bring the entire project on your local computer!

## 2. Clone the repository

After step 1, you will land on your forked repo page, here you will see a `<>` button marked in green, click on it and copy the url.

<img width="411" alt="Screenshot 2023-05-29 at 11 47 49" src="https://github.com/fernandezbaptiste/Your-First-Contribution/assets/83458751/4a0f5bbc-854a-4df0-845d-fa8266414264">

Open your terminal, move to a directory of your choice (maybe more can be expanded her- or drop a link) and run the following git command:

`git clone "url you just copied" `

[screen shot] 

## 4. Open File and Make changes

The entire project is now on your computer! 

Now, make sure from your terminal that you are now in the project by running:
`cd Your-First-Contribution`

Now open OurStory.txt file in on your favorite IDE or even just a text editor. 

Here you will see the project which you will contribute to.
The project is a story being built many developers around the planet, all one by one by adding the next latest sentence at the end of the file.

Now its your turn 🤩

Add up one or two sentences that you think would make sense in the story line.

Save the file 

## 5. Send your changes to your personal Repo

In your terminal, type 
`git add . ` 

right after type
`git commit -m "your name" `

and finally
`git push ` 

Github will ask you to authenticate yourself with your username and password. 
For password, ever since Agu 2021, it is no longer your actual password they need but actually a personal token. 

To get this token, head on github to: profile setting -> developer setting -> Personal Access Tokens (Token Classic) -> Generate new token (classic) -> give a name e.g "authentification token" -> select the scopes you want (for ease you can select all of them) -> click on Generate token

Your token will be displayed and you will be able to paste it in your terminal after which your push should have been succesful! 

In here, we have essentially "added" all the changes, added a commit message (which helps telling other devs what you have changed) and pushed the changes into your online github repository. 

## 6. Convert your changes from your repo to the original repo 

Go now to your forked github repo page online, `sync` your fork and then there you will see a button in green which says `Open Pull request`
Open pull request
, press it and in the comments section type "Adding my name to contributer list" and press on 



If you go to the project directory and execute the command git status, you'll see there are changes.

Add those changes to the branch you just created using the git add command:

git add Contributors.md
Now commit those changes using the git commit command:

git commit -m "Add your-name to Contributors list"
replacing your-name with your name.



Celebrate your contribution and share it with your friends and followers by going to web app.

You could join our discord team if you need any help or have any questions.

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out the list of projects in the web app.
