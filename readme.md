# DM-GY 9103 Mobile Apps

![NYU](http://ws2.polishedsolid.com/de/nyu_soe_logo.png)

# http://tiny.cc/ios2016

### Basic Information
* Be sure to read the [syllabus](syllabus.md)

### Getting Started
* [Sign up for an Apple Developer Account](https://developer.apple.com/membercenter/) if you don't have one
* Sign up for a github account and [the student developer pack](https://education.github.com/pack)
* Join the class [slack team](https://nyu-ios.slack.com) (click on "create an account")
* Please fill out [this google form](http://goo.gl/forms/AogDF1iW9l) with your contact information
* Setup your git repository for textbook work.
* Download [Xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12) from the OS X App Store

### Setting up your git Repository
(These are the instructions for setting up a public repository, which is recommended)

* Go to the [coursework git repository](https://github.com/IDMNYU/DM-GY-9103-SP16-CourseWork.git)
* Create a fork of the repository under your own github account (button is currently on the upper right of the page)
* On the page for your fork, copy the SSH Clone URL (should look like `git@github.com:/YourGithubUsername/DM-GY-9103-SP16-CourseWork.git`)
* In your terminal, type the following commands (here's a basic [guide](https://mattwilcox.net/archives/a-very-basic-introduction-to-the-command-line-terminal-and-shell/) if you're just getting started):
* `cd place/you/want/to/do/your/work`
* `git clone https://github.com/YourGithubUsername/DM-GY-9103-SP16-CourseWork.git` (replace with your URL)
* `cd DM-GY-9103-SP16-CourseWork.git`

* `touch testfile`
* `git add .`
* `git commit -m 'adding a blank test file to make sure everything works'`
* `git push origin master`


### Submitting Work

As you go through the book, you'll be coding along with the examples in the book. As a general rule, any time the author writes something like "now try running your code, it should work", and your code works, it is time to commit. Commit with the following commands:

If you want to push up everything you've done, mark everything for commiting with:

* `git add .`
* `git commit -m 'finished chapter 1, page 12'`
* `git push origin master`

Progress on the book work will be self-reported, using a google form, before the start of the class. **WILL BE PUBLISHED SHORTLY**

Work will be due the day of class (for example, Chapter 2 "The Swift Language" is due on 2/2). Each student will get 3 one week extensions to use throughout the semester.

