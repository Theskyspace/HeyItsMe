# Make Your First Contribution 😎
Hey this is Akash and I invite you to make your First commit ever in this repo by sharing your social handles so that like minded can get along with you.

After Following the following steps you can find your name card on this [site.](https://theskyspace.github.io/HeyItsMe.github.io/)

# Here's How you can do it
This article is take from [FirstContributions](https://github.com/firstcontributions/first-contributions)<br>

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-alonzo-church
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

1. Open Index.html and add the following code.
  ```html
  <div class="card">
      <img src="https://media.giphy.com/media/ekjmhJUGHJm7FC4Juo/giphy.gif?cid=ecf05e47dwrju7x86gobs0ytiqkf12vi26sha8uy0pkgbzc9&rid=giphy.gif&ct=g" alt="" class="card__img">
      <div class="card__content">
        <div class="card__info">
          <h2 class="card__name">Your-name</h2>
           <!-- Line that describes you-->
          <span class="card__prof">Just a Enthu Programmer</span>
        </div>
        <div class="card__icons">
          <div class="card__icon-container-t">
            <a href="Link to your twitter handle" target="_blank"><box-icon type='logo' name='twitter' color='white'></box-icon></a>
          </div>
          <div class="card__icon-container-t">
            <a href="Link to your instagram handle" target="_blank"><box-icon name='instagram-alt' type='logo' color='white'></box-icon></a>
          </div>
          <div class="card__icon-container-i">
            <a href="Link to your linkedin handle" target="_blank"><box-icon name='linkedin' type='logo' color='white'></box-icon></a>
          </div>
        </div>
      </div>
    </div>
  ```
2. After making edits, paste the code in the ```index.html``` file, wherever it is mentioned to copy!

3. Now save the ```index.html``` file and open it using browser! If your card is successfully created, Now Its the time to go to next otherwise debug it.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add index.html
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.


## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

<h2 align=center> ✨ Contributors </h2>


Thanks go to these **Wonderful People** 👨🏻‍💻:      🚀 **Contributions** of any kind are welcome! 

<table>
<a href="https://github.com/Theskyspace/HeyItsMe/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Theskyspace/HeyItsMe" />
</a>
</table>
