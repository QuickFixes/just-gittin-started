#Robotics+IEEE QuickFix #1: Git and GitHub

This repository hosts reference materials and a sample repo for a hands-on Git/GitHub seminar.

## What you'll need to get started

### tl;dr version
1. [Sublime Text](http://www.sublimetext.com/) (cross-platform, free to try)
2. the official GitHub client for your platform ([Mac](http://mac.github.com), [Windows](http://windows.github.com))
3. On Linux: `<your package manager's install command> git-core` plus [`git-cola`](http://pkgs.org/search/git-cola) (KDE) or [`giggle`](http://pkgs.org/search/giggle) (Unity/GNOME/XFCE) if you want something a bit nicer than `gitk` for visualizing your source tree.

### Longer explanation
We know that not everyone at our workshop will be eager to dive into a [Unix shell](https://ucfilespace.uc.edu/wiki/search/Unix%20Access%20on%20UCFileSpace) and start using [Vim](http://vim.org) and console `git` commands. So out of consideration for folks without much command-line experience, and for consistency, we'd like everyone to install [Sublime Text](http://sublimetext.com) the official GitHub [GUI](http://windows.github.com) [clients](http://mac.github.com) **before coming to the seminar**.

These are straightforward, one-double-click installs for Mac and Windows.

*  Sublime Text is available for all three major OSes (not Amiga, sorry), has good out-of-the box keybindings and syntax highlighting, and pretty good Git integration [with a plugin](https://github.com/kemayo/sublime-text-git) (for more advanced users).
* The official GitHub client for Windows includes a self-contained installation of the Git command-line tools, and a colorized Powershell Git environment, which saves you the effort of installing msysGit or some other distribution. (Recent versions of Mac OS X already have `git` installed, and Terminal.app should be somewhere in your "Applications" folder.)

All that being said, if you're comfortable using some other text editor (that is _not_ Microsoft Word, sorry) and/or prefer to do all your Git stuff from the command line, that's just fine. Just realize that we simply won't have time to work out installation issues if you stray too far off the path.

##Resources on the Web

_The [References](/QuickFixes/just-gittin-started/wiki/References) article in this project's wiki is **very** comprehensive, and already includes most of the references listed below. It's organized by skill level, so you can tell at a glance which ones are useful to you._

### References
2. [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) - on GitHub.com; Markdown is the markup language used in GitHub issues, comments, and the default `README.md` for new repositories
3. [Documentation on git-scm.com](http://git-scm.com/doc) - online help, videos, and ebooks, straight from the source
4. [GitHub Help](https://help.github.com/) - comprehensive online help that covers Git _and_ GitHub topics
5. [git ready](http://gitready.com/) - cookbook-style help for Git, when you already sort of know what you're trying to do but maybe don't know the precise Git nomenclature for it
6. [Highest voted questions tagged 'git' on Stack Overflow](http://stackoverflow.com/questions/tagged/git?sort=votes&pageSize=15)

### Videos
1. [Webcast • The Basics of Git and GitHub • July 2013](https://www.youtube.com/watch?v=U8GBXvdmHT4) - a 50-minute webcast hosted by a GitHub employee that provides a high-level overview of what Git is, why you'd want to use it, and how GitHub.com layers extra collaborative features on top of Git <abbr title="Source Code Management">SCM</abbr>.
2. [GitHub Training & Guides](https://www.youtube.com/channel/UCP7RrmoueENv9TZts3HXXtw) YouTube channel (check out their [video intro](https://www.youtube.com/watch?v=y04-NzarItQ) for a quick chuckle)
3. [GitHub Guides: GitHub & Git Foundations](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-) - bite-sized videos covering one Git or GitHub topic each (_e.g._, `git diff`, `git rm`, branch, checkout, and merge) 
4. [Jessica Kerr: "Git Happens"](https://www.youtube.com/watch?v=Dv8I_kfrFWw) - a 54-minute conference talk which explains Git concepts like branching, merging, and rebasing in a highly visual way. Good if you're compfortable with basic Git usage, but have always wondered about more advanced usage like branching and rebasing. If you stick with it until the end, you'll be rewarded with an epiphany about `git rebase -i`. Promise.
5. [Michael Schwern: "Git for Ages 4 and Up"](https://www.youtube.com/watch?v=1ffBJ4sVUb4) - a demonstration of advanced Git functions (branch, merge, rebase) using Tinker Toys. Over an hour long, but totally worth it for the epiphanies you'll have about HEAD, tags, branching, and merging, if you didn't really "get" those concepts before.

### Tutorials
I highly recommend Git Immersion (created by locals at [Neo](http://neo.com)) for hands-on learning with the Git command-line tools. For these exercises, you can use UCFileSpace for [shell access](https://ucfilespace.uc.edu/wiki/search/Unix%20Access%20on%20UCFileSpace) and UC's [GitHub Enterprise server](https://github.uc.edu) as the remote "origin" repository, if you wish.

* [Git Immersion](http://gitimmersion.com/)

Neo's tutorial helps you install Git on your workstation (but you can [use UCFS for that][ucfsqf]), gets you up-and-running with a sane Git configuration, walks you through all of the common commit/push/merge operations, and even forces you to break (and fix) things in some of the advanced lessons. Each lesson is short, and easy to go back and reference later when you run into trouble on a _real_ project. Although the tutorial's sample project is comprised of Ruby code, no familiarity with the [Ruby language](http://ruby-lang.org) is actually required to complete the tutorial.

[ucfsqf]: /QuickFixes/lost-in-ucfilespace
