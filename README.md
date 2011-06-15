# GitHub Terminal

This is an example application written to demonstrate what is possible with the new GitHub Git Data API and GitHub OAuth2 services. This app allows you to login as your GitHub user and edit and commit groups of files through a virtual terminal.

# Features

Currently, you can:

* List all the projects you have read and write access to.
* `cd` into any project and branch and `ls` as if it were a directory.
* Edit any file in a project you have write access to.
* Commit your edited files directly to your GitHub branch.
* View status of changed files with `status` and unstage them with `unstage` command.
* View the commit log of any branch with `log` command.

# Screenshots

![list projects](https://img.skitch.com/20110615-1i4r8dub96267e7fdswhuqcerx.png)

Here we can see a listing of my projects, in this case with a filter on the string 'git-'.

![list tree](https://img.skitch.com/20110615-rq4ccy7gg49nrm25rp2j1swkdg.png)

You can `cd` into a project and a branch, then an `ls` will show you the project tree.

# Contributing

If you want to fix or change something, please fork on GitHub, push your change to a branch named after your change and send me a pull request.

Some ideas of things to do are in the TODO file.

# License

MIT, see LICENCE file

