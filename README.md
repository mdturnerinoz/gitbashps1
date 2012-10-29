This file is intended to be included directly (as in, copied) or 
indirectly (as in using the source or "." command) into the likes of 
.bash_login or similar location (i.e.  so it can be invoked anytime you 
login or create a new window under the like of Konsole, Terminal, or such.  

Once you do so, the value of $PS1 will be changed such that you will now 
see the name of the currently set git branch (if in a git repos); this 
will save always having to do a "git brach" to see where you are.  

The contents of the gitbashps1 file is fairly common knowledge, so I take 
no credit (nor responsibility) for its contents are actions (or lack 
thereof) since it represents knowledge fairly common on "the net".  

I just put it at github hoping it would be useful and so that I don't have 
to remember how to do it the next time I tell a colleague about it: I just 
have to point them at this repos.  

source ~/.gitbashps1 
       OR
. ~/.gitbashps1

Place in one of the following bash files configuration (~/.bash_login, 
~/.bashrc, or ~/.bash_profile) as you choose (this depends on how you normally 
use bash as well).  While I haven't tested this, I believe that it should 
work with zsh or other bash-clone shells.  

Output once in place will be similar to the following; change the bash 
flags within .gitbashps1 as needed: 

macmini2:gitps1 marty [master] $ 

Marty Turner 23 October 2012
mdturnerinoz@gmail.com