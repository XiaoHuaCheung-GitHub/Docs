 # verify-commit 
GIT-VERIFY-COMMIT(1)                                                                              Git Manual                                                                             GIT-VERIFY-COMMIT(1)

NAME
       git-verify-commit - Check the GPG signature of commits

SYNOPSIS
       git verify-commit <commit>...

DESCRIPTION
       Validates the GPG signature created by git commit -S.

OPTIONS
       --raw
           Print the raw gpg status output to standard error instead of the normal human-readable output.

       -v, --verbose
           Print the contents of the commit object before validating it.

       <commit>...
           SHA-1 identifiers of Git commit objects.

GIT
       Part of the git(1) suite

Git 2.18.2                                                                                        01/03/2020                                                                             GIT-VERIFY-COMMIT(1)
