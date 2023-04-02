### Testing Git 

- This repository is only to test git and github

### We are learning many git command
                    
Commands  | Descriptions
------------- | -------------
git clone #url-http-repository | Clone repository
git init | Init project
git remote -v  | Name repositories remote
git add .  | Add changes
git commit -m #message  | Create commit
git commit --amend | Overwrite last commit
git pull origin main | Download changes from remote repository
git push origin main | Upload changes from remote repository
git branch #name-branch | Create branch
git branch -d #name-branch | Deleted branch
git checkout #name-branch | Enter into a branch 
git merge #name-branch | Merge branches
git log --all --graph --decorate --oneline | History changes
git status | Status local repository
git tag -a #name-tag -m #message #number-commit-reference | Create tag
git tag | See tags
git show-ref —tags | See tags with reference
git push origin --tags | Send tag to remote repository
git tag -d #name-tag | Delete tag
git push origin :refs/tags/#name-tag | Delete tag in remote repository
git config --global user.name #name | Config user name
git config --global user.email #email | Config user email
git config --global --edit | Edit config
gh auth login | Login again in github
git show-branch --all | Structure project
git diff | See difference
git rebase #name-branch | Rebase
git stash | Save temporal changes
git stash list | See all stash
git stash drop | Delete stash
git stash branch #name-branch | Create a branch with stash adding
git clean --dry-run | Show files for clean
git clean -f | Execute clean file
git cherry-pick #ref-commit-other-branch | Merge commit ref from another branch in the branch actual
git reflog | Show all changes and history
git reset --hard #ref-commit | Return change to reference commit, remenber use push force
git grep #word | Search word in the branch
git grep -c #word | Time appear a word in branches
git log -S "#word" | Time appear a word in commits
git shortlog -sn | Count commits by contributor
git shortlog -sn --all --no-merges | Count commits by contributor no merge
git config --global alias.stats "shortlog -sn --all --no-merges" | Create alias
git blame #file | Information changes people
git blame #file -L1,10 | Information changes people in lines
git #command --help | command to help
git branch -r | Show remote branches
git branch -a | Show all branches


### More information about Git

[Hashcode Cris Programming](https://crisprogramming.hashnode.dev/)

### Editor MD
[Editor MD](https://pandao.github.io/editor.md/en.html)
