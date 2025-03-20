# git_branch
learnig git branching

# Define terms
-Branch
-1. Isolation
-2. parallel development

# git commands
1.create a branch
'''bash 
     git branch "branchname"
'''

2.switcing between branchesF
'''bash
      -git switch branchname
      -git checkout branchname
'''

 -directly swiching to a neew branch
'''""""
    git checkout -b branchname
'''

3.merging
'''""""
    git merge sourcebranch
'''

4.Resolving conflicts
"""bash
    git mergetool
"""
5.list all branches
"""git branch"""
'''git branch-v'''

git status
-list of extra commands

list merdged
git branch--merged
-list umerged commits
"""git branch --no-merged"""