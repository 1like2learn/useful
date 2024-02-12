git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.lg "log --oneline --decorate --graph --all"
git config --global alias.alias "! git config --get-regexp ^alias\. | sed -e s/^alias\.// -e s/\ /\ =\ /"
git config --global alias.pl "pull --rebase origin"
git config --global alias.cm "commit -m"
git config --global alias.psh "push origin HEAD"
git config --global alias.mend "commit --amend"
git config --global alias.cont "rebase --continue"
git config --global alias.oops "reset --soft HEAD^"
git config --global alias.up "pull --rebase"
git config --global alias.pub "add .; git mend; git psh"
git config --global alias.cp "cherry-pick"
