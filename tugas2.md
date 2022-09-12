# __Chapter 1. Introduction__

In this chapter I’ll start by introducing Git and GitHub. What are they, what is
the difference between them, and why would you want to use them? I’ll then
introduce some other common terms that you’ll often hear mentioned when
people are discussing GitHub. That way you’ll be able to understand and
participate in discussions about your projects more easily.


## __What is Git?__
Git is a version control system. A version control system is a piece of software
designed to keep track of the changes made to files over time. More specifically,
Git is a *distributed* version control system, which means that everyone working
with a project in Git has a copy of the full history of the project, not just the
current state of the files.

## __What is GitHub?__
*GitHub* is a platform where you can upload a copy of your Git repository (often
shortened to repo), hosted either on GitHub.com, by your company on a cloud
provider (like Azure, AWS, or IBM Bluemix), or on your company’s own
servers behind its firewall. But more than just uploading your Git repositories, it
allows you to collaborate much more easily with other people on your projects.
It does that by providing a centralized location to share the repository, a web based interface to view it, and features like forking, Pull Requests, Issues,
Projects, and GitHub Wikis that allow you to specify, discuss, and review
changes with your team more effectively.

## __Why Use Git?__
Even if you’re working on your own, if you are editing text files, there are a
number of benefits to using Git, including the following:

<br>

The ability to undo changes

* If you make a mistake, you can go back to a previous point in time to recover
an earlier version of your work.

<br>

A complete history of all the changes

* If you ever want to see what your project looked like a day, week, month, or
year ago, you can check out a previous version of the project to see exactly
what the state of the files was back then.


Documentation of why changes were made

* Often it’s hard to remember why a change was made. With commit messages
in Git, it’s easy to document for future reference why you’re making a
change.

<br>

The confidence to change anything


* Because it’s easy to recover a previous version of your project, you can have
the confidence to make any changes you want. If they don’t work out, you
can always get back to an earlier version of your work.

<br>


Multiple streams of history


* You can create different branches of history to experiment with different
changes to your content or to build out different features independently. You
can then merge those back into the main project history (master branch)
once they’re done, or delete them if they end up not working out.