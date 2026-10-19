# The Adventure of the Abbey Grange

*A Sherlock Holmes mystery played through Git.*

You are Sherlock Holmes. Dr. Watson has kept a version-controlled record of a quite remarkable case.

Investigate the evidence, follow the history and draw your deductions.

## How to Play

Explore Watson's records, commits and branches using:

```bash
git log --all --oneline --graph
git branch -a
git show HEAD
```

New case-files will appear under `case/` as the investigation advances.

Write your answer in `deduction.txt`, then commit and push it.

Once GitHub Actions completes, retrieve the latest records using:

```bash
git pull --rebase
```

## Begin the Investigation

Open `deduction.txt` and enter:

```text
G0=START!
```

Then run:

```bash
git add deduction.txt
git commit -m "START!"
git push
```

**The game is afoot!**
