# Git

In the previous section, you learned the basics of `git`. Now we’ll take the next step by using **Github Classroom**. Github Classroom is a platform that makes it easy for teachers and students to work with GitHub repositories in a course setting. It automatically sets up a personal repository for each student, so you can manage your project in a structured way while your teacher can keep track of your progress.

1. Create an account on [github.com](https://github.com/) if you haven’t already.

2. Go to [Github Classroom to create a new repository for your project](https://classroom.github.com/a/wI9VhW9_).

3. Clone the repository to your computer (see below).

## Tips

* Make sure you **never** edit files directly via the github.com website. Use `git` on your own computer and `push` the changes to Github.

* `git` has a steep learning curve you need to get through. The real learning happens by using `git`. Over time it will become second nature. Until then it might feel a bit frustrating and unfamiliar, but that’s normal!

* If you unexpectedly run into a "merge conflict," you might need some help. It’s not recommended to rely on random internet sources—you often can’t judge whether the advice fits your situation. We’ve seen people lose work because of this.

## Using Git

You’ve already learned about `git`. Make sure you know the basic commands, and **do not** use the git integration in Visual Studio Code or another graphical program. This actually makes things more complicated until you fully understand `git`.

The terminal commands you need for using git:

* `git clone https://github.com/...` to get the repository you created onto your computer and link it to the Github repository

  * afterwards, you can use `cd` to move into your project directory

* `git status` to see which files have changed

* `git add -A` to stage all changes for a commit

  * or `git add filename.py` to stage a single file for a commit

* `git commit -m "description of this commit"` to record the day’s work

* `git push` to sync your work with Github.com

To revert a file back to the version from the previous commit (discarding all of the day’s changes), you can use:
Do this very carefully, because once it’s gone, it’s really gone!

* `git checkout -- filename.py`

It’s also possible to undo things you’ve already committed and pushed. However, this is not as straightforward as using the basic commands. Ask for help with this.

