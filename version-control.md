#Git

### Show file content at a commit
    git show <sha1-of-commit>:path/of/file

### Remove local untracked files
    git clean -f

### Restore content of a directory at commit
    git checkout <sha1-of-commit> -- path/of/directory

### Create remote branch with git-svn
    git svn branch -m "Branch creation message." branch-name
    git checkout -b branch-name remotes/branch-name

### Create remote branch from commit with git-svn
    git checkout <sha1-of-past-commit>
    git svn branch -m "Branch creation message." branch-name
    git checkout -b branch-name remotes/branch-name
