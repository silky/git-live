git-live
==

A thing that lets you work on code file live with your friends.


usage
--

1) install [Commando](https://github.com/sordina/Commando)

2) run `commando -c git-live | grep --line-buffered -v '.git'` in your directory.

Then `git-live` will, upon every file save action, add everything, commit everything, pull down changes, merge them automatically, and continue on in that fashion.
