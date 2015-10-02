git-live
==

A thing that lets you work on code file live with your friends.


usage
--

1. Install [Commando](https://github.com/sordina/Commando)
1. Install [Conscript](https://github.com/sordina/Conscript)
1. Run `commando -c echo | grep --line-buffered -v '.git' | conscript git-live` in your directory.

Then `git-live` will, upon every file save action, add everything, commit everything, pull down changes, merge them automatically, and continue on in that fashion.
