# Instructions

This repository includes some basic instructions and description of some terms.

## Terms

### git
Git is a version control tool which is used to allow multiple people to contribute to same code.

**example**

There is an organization which has three developers and they are each individually developing new features for the same product. In this examample each programmer would have their own copy of the code and make changes to that code. The question is how to combine the code together. Git allows programmers to track their changes and use it to combine their changes with other people. Basically it means that if programmer 1 modifies file 1 and programmer 2 modifies file 2 git knows own to combine these changes. In this case it is easy to combine since git just needs to add file 1 from programmer 1 and file 2 from programmer 2. 

What if programmers modify the same file ? No worries git can automatically merge these files so that merged file contains newest changes from programmer 1 and programmer 2.

#### Commands

```bash
# clones repository from url
# clone is similar to copying the 
# project and its files to your computer.
git clone URL

# Pulls changes from another repository
git pull

# Push changes to another repository
git push

# Commit changes
git commit -m "Commit message"
```

### JavaScript / TypeScript

JavaScript is a programming language 
used in web programming but also 
in backend development.


