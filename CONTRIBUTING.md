# How to make your first contribution?

This documentation is to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, please follow the steps below.

<img align="right" width="300" src="https://user-images.githubusercontent.com/78134633/197248414-712abae3-a562-4aef-a802-6d48115de565.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will result in a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://user-images.githubusercontent.com/78134633/197248532-b81b898d-1f14-4583-af12-66ea352b6c11.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://user-images.githubusercontent.com/78134633/197248603-671d278f-b007-44b0-8c80-52a9b04f4616.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/GitFest.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd GitFest
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-new-file
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open add or edit file in a text editor. Add code for any existing algorithm in other language or add some new algorithms. Make sure to update correspond README.md file if needed. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add "name of the file you add or edit"
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add message for the change"
```

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://user-images.githubusercontent.com/78134633/197248689-cf80da0d-376a-4ec4-a3e0-7c026a31b276.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://user-images.githubusercontent.com/78134633/197248751-c6094f0e-7585-4999-a4d1-27d54b7ccd3a.png" alt="submit pull request" />

Soon after reviewing all your changes will be merged into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!
