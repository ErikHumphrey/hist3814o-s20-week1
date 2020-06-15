# Notes — Week 1

## Setting up GitHub

### Creating an account

* Having already used GitHub in the past, I was able to skip the account creation step.

### Setting up a repository

* After creating a new repository on GitHub, I went ahead and created repositories for Weeks 2–6 as well.
  * Although people visitng the repositories later might get the wrong impression of when I started them due to the first commit date of each repository, I felt this was worth doing all at once.
* As I already had Git installed, my intuition was to use `git clone` to clone all the repositories to a DIGH 3814 directory on my computer, which would make it easier for me to modify the repository without access to the Internet, pushing changes to the repository later. It would also make it easier to edit files in a text editor of my choice, or add and remove files using my operating system's file manager.
  * For this course, I mostly used Windows's File Explorer, but sometimes also used macOS's Finder.
  * As the instructions state, it's possible to drag files onto GitHub to add them to a repository, but I chose this method so I could also drag files out of the repository (moving them to another directory), rather than deleting them.

### Making a new text file

* I created a file "markdown-test.md" and put it in the local folder that was made when I cloned the repository.
* I edited this file to test out Markdown features on GitHub, including headings, bold and italics, hyperlinks, separators, images, quotes, code, lists, and paragraphs.
  * To preview my changes from my offline text editor, I used Visual Studio Code's built-in live Markdown preview, though it has its own way of interpreting Markdown. As such, some things like "@username mentions" or task lists (like with `- [x]` and `- [ ]`) wouldn't show by default in my text editor's preview, as they're not supported. 
  * If I remember, I try to leave a blank empty line at the end of every text file I create, as GitHub tends to leave a warning about it for code-related reasons. There are some ways to do this automatically, such as the process of "linting" text files.

### Uploading a file to GitHub

* Once I was happy with my changes to the file, I ran `git add markdown-test.md`, used `git commit -m` to commit the changes with a message, and then `git push` to make the change appear in the remote GitHub repository along with the file.
* I then created a new "evidence" folder to put it in, in order to separate it from my journal.md, notes.md, and README.md. I was able to add this with `git add evidence/` before committing it, which also tracked all of its contents.
* Though I've used GitHub to run a website in the past, which proved quite useful, I felt it would be an unnecessary excess of work to use it for showing my progress in this course, so I elected not to. Having looked ahead in the course, it looks like GitHub Pages will be used to generate a static website later on in Week 6, anyway.
* For fun, I also followed [GitHub's instructions on generating a GPG key to sign commits](https://help.github.com/en/github/authenticating-to-github/managing-commit-signature-verification), putting a nice "Verified" status on each commit to authenticate that I made them, as many aspects of Git commits, including authors, can [be faked](https://github.com/jayphelps/git-blame-someone-else).

### Setting up Hypothesis 

* I didn't have any immediate issues setting up Hypothesis or installing its Chrome extension.
* I noticed that when trying to annotate something with Hypothesis, it would often say that I was logged out despite having logged in before, especially if it was on a website I hadn't visited before. Luckily, a single click would log me back in. 
* I found it nice that some websites could have Hypothesis enabled by default, like the course website, rather than having to click the Chrome extension's icon to activate it.
* It also found it useful that Hypothesis annotations share some Markdown syntax.
* I created an annotation with "Only Me" visibility with the "hist3814o" group to test it out. I probably could have done this more quickly by attaching a note to a highlight, as highlights are only visible to me to begin with.
* I like the collaborative features of Hypothesis.

### Setting up Zotero

* I wish Zotero was only a browser extension like Hypothesis and I didn't have to install any desktop software, but I suppose it's not a big deal.
* This could be quite useful software, as I've gotten into a bad habit of screenshotting things to remember them without (1) making a note of why I screenshotted the item or needed to remember it and (2) actually going back to review my Screenshots folder on a regular basis.
* I like the ability to organize saved items with Zotero.

## Asking for help

* Though this was useful information, I feel I already knew about much of it.
* Rather than using Screencastomatic for screenshots and screenvideo, my tool of choice is [ShareX](https://getsharex.com/).

## Getting started with Discord

* As I've used Discord in the past, I briefly skimmed the instructions to see if there was anything new to know, though there wasn't.
  * I did learn more about Alex, though!
* As Discord was already set up and configured, I was good to continue!
