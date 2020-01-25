# Answers:
1. What does 'git log' look like?
C:\Users\Raiki\Documents\GitHub\191-Jeimeil-Rey-Rosal-Mercado>git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

2. After creating file, what does git status look like now?
commit 9936afe693d0c96b5c6f970646c999188ea3ba1c
Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
Date:   Fri Jan 24 18:18:09 2020 -0800

    Create README.md

commit 1a2f9c4d12c8a7c2b7c5f7d33dd1861b4ac57e76
Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
Date:   Fri Jan 24 18:13:37 2020 -0800

    Katas

3. Add file to staging area, git status
commit 049bd27f13b628e0f446e4532474d1890ff7a01c
Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
Date:   Fri Jan 24 18:23:24 2020 -0800

    Update README.md

4. Change content:

commit 049bd27f13b628e0f446e4532474d1890ff7a01c
Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
Date:   Fri Jan 24 18:26:21 2020 -0800

    Update README.md

5. Change Content:

Same as above

6. Commit:
commit 0f4158cea9483b0912122abd4298ddb17fc1141b (HEAD -> master, origin/master)
Author: JeiRey <47876392+JeiRey@users.noreply.github.com>
Date:   Fri Jan 24 18:30:27 2020 -0800

# Git Kata: Basic Commits
This kata will introduce you to the `git add` and `git commit` commands.

This is a very introductory kata. if you have used `git status`, `git log --oneline --graph`, `git add` and `git commit` extensively you should probably skip it.

You can look at the bottom of this file, if you have not yet done basic git configuration.

## Setup:

1. Run `. setup.sh` (or `.\setup.ps1` in PowerShell)

## The task

1. Use `git status` to see which branch you are on.
2. What does `git log` look like?
3. Create a file
4. What does the output from `git status` look like now?
5. `add` the file to the staging area
6. How does `git status` look now?
7. `commit` the file to the repository
8. How does `git status` look now?
9. Change the content of the file you created earlier
10. What does `git status` look like now?
11. `add` the file change
12. What does `git status` look like now?
13. Change the file again
14. Make a `commit`
15. What does the `status` look like now? The `log`?
16. Commit the newest change

## Useful commands
- `git add`
- `git commit`
- `git commit -m "My commit message"`
- `git log`
- `git log -n 5`
- `git log --oneline`
- `git log --oneline --graph`
- `touch filename` to create a file (or `sc filename ''` in PowerShell)
- `echo content > file` to overwrite file with content (or `sc filename 'content'` in PowerShell)
- `echo content >> file` to append file with content (or `ac filename 'content'` in PowerShell)


## Git Initial Configuration
1. `git config --global user.name "John Doe"`
1. `git config --global user.email "johndoe@example.com`

For the vim scared:
- `git config --global core.editor nano`

For the windows peeps:
- `git config --global core.editor notepad`

Other editor options:
- `git config --global core.editor "atom --wait"`
- `git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst"`
