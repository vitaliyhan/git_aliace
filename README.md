# git_alias
 acp command to add all + commit + and push

alias.acp=!f() { git add -A && git commit -m "$@" && git push; }; f

usage:
acp "text"


all current aliases u can get in git config -l  
