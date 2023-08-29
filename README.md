# Git Tutorial

This repository is used for learning [Git](https://git-scm.com/).

## Working with branches

List of steps:

1. Clone repository.

    ```text
    git clone git@github.com:pkudzia1/git-tutorial.git
    ```

2. Go to `git-tutorial` directory.

    ```text
    cd git-tutorial
    ```

3. Create `TASK-1` branch.

    ```text
    git branch TASK-1
    ```

4. Check list of branches in local repository (`main`, `TASK-1`).

    ```text
    git branch
    ```

5. Switch to `TASK-1` branch.

    ```text
    git checkout TASK-1
    ```

6. Create `task1.php`.

    ```text
    touch task1.php
    ```

    ```php
    <?php

    echo 'Hello TASK-1!';
    ```

7. Add all files from current directory to staging area to track unversioned files.

    ```text
    git add .
    ```

8. Create commit.

    ```text
    git commit
    ```

9. Push local changes to given branch from remote repository.

    ```text
    git push origin TASK-1
    ```

10. Switch to `main` branch.

    ```text
    git checkout main
    ```

11. Create `TASK-2` branch.

    ```text
    git branch TASK-2
    ```

12. Check list of branches in local repository (`main`, `TASK-1`, `TASK-2`).

    ```text
    git branch
    ```

13. Switch to `TASK-2` branch.

    ```text
    git checkout TASK-2
    ```

14. Create `task2.php`.

    ```text
    touch task2.php
    ```

    ```php
    <?php

    echo 'Hello TASK-2!';
    ```

15. Add all files from current directory to staging area to track unversioned files.

    ```text
    git add .
    ```

16. Create commit.

    ```text
    git commit
    ```

17. Push local changes to given branch from remote repository.

    ```text
    git push origin TASK-2
    ```

18. Switch to `main` branch.

    ```text
    git checkout main
    ```

19. Merge `TASK-1` branch to `main` branch.

    ```text
    git merge TASK-1
    ```

20. Push local changes to given branch from remote repository.

    ```text
    git push origin main
    ```

21. Check list of branches in local repository (`main`, `TASK-1`, `TASK-2`).

    ```text
    git branch
    ```

22. Merge `TASK-2` branch to `main` branch. (Commit message: `Merge branch 'TASK-2'`).

    ```text
    git merge TASK-2
    ```

23. Push local changes to given branch from remote repository.

    ```text
    git push origin main
    ```

24. Check list of branches in local repository (`main`, `TASK-1`, `TASK-2`).

    ```text
    git branch
    ```

25. Create `TASK-3` branch.

    ```text
    git branch TASK-3
    ```

26. Check list of branches in local repository (`main`, `TASK-1`, `TASK-2`, `TASK-3`).

    ```text
    git branch
    ```

27. Switch to `TASK-3` branch.

    ```text
    git checkout TASK-3
    ```

28. Edit `README.md`.

29. Add all files from current directory to staging area to track unversioned files.

    ```text
    git add .
    ```

30. Create commit.

    ```text
    git commit
    ```

31. Push local changes to given branch from remote repository.

    ```text
    git push origin TASK-3
    ```

32. Switch to `main` branch.

    ```text
    git checkout main
    ```

33. Merge `TASK-3` branch to `main` branch.

    ```text
    git merge TASK-3
    ```

34. Push local changes to given branch from remote repository.

    ```text
    git push origin main
    ```

35. Check list of branches in local repository (`main`, `TASK-1`, `TASK-2`, `TASK-3`).

    ```text
    git branch
    ```

36. Check working tree status.

    ```text
    git status
    ```
