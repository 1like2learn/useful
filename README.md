co = checkout
br = branch
ci = commit
st = status
lg = log --oneline --decorate --graph --all
alias = ! git config --get-regexp ^alias\. | sed -e s/^alias\.// -e s/\ /\ =\ /
pl = pull --rebase origin
cm = commit -m
psh = push origin HEAD
mend = commit --amend
cont = rebase --continue
oops = reset --soft HEAD^
up = pull --rebase
pub = add .; git mend; git psh
cp = cherry-pick# useful
