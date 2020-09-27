# README #


### What is this repository for? ###

* To maintain the PNWDigital CSV (Comma Seperated Value) files that are used with Andrew's [ACB](https://github.com/K7ABD/anytone-config-builder) to create the stock Community Codeplugs

### How do I get set up? ###

If you just want a copy of the latest CSV files you can easily download them directly from the bitbucket repository page by clicking the '...' icon at the top right of the repo.

There can be a bit of a learning curve with git and Bitbucket, but it's worth it if you want to create and maintain any kind of source files for a project, especially if a team of people are involved. There are many good git/bitbucket [tutorials](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud) on the web that will get you started, and there are git GUIs if you're not a command-line jocky. 

[Git for Windows](https://gitforwindows.org/) 

[Git for Mac](https://git-scm.com/download/mac)

Briefly speaking, if you want to contribute corrections or additions to the CSV files the process will look something like this:

* First clone the repository to your local machine
* Next make the changes
* Throughly test the changes using ACB, CPS (Anytone's Consumer Programming Software), and your radio(s) to verify your changes are working as expected
* Commit the changes
* Create a 'pull request'. This alerts the admin(s) of the repository that there are changes to be reviewed and merged into the master files
* Take pride that you contributed to the greater good of the PNW DMR codeplug community!


### Contribution guidelines ###

* Remember to run 'git pull' to get the latest updates into your local copy before you start editing. This will help avoid version conflicts.
* Make sure to throughly test your changes to ensure ACB is properly processing your modified CSV files, and CPS is properly importing the files produced by ACB
* Add a brief comment to document what you changed 
* Beware of changing the line endings in the CSV files. Currently ACB only works with DOS-style line endings (CRLF). Editing the CSV files using a CSV editor on Linux may result in changing the line endings (CR). If you use Linux, the unix2dos utility should be helpful. 

### Who do I talk to? ###

* Repo owner or admins to request to be added to the 'developer' group to submit changes (create pull requests)
* Other community or team contact