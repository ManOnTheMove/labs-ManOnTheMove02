## Labs

*Don't make copies of files. These are yours. Edit them and save. For labs, edit `labXX.Rmd` and knit. Then commit both `labXX.Rmd` and `labXX.pdf`.*

This repository contains (or will contain) all of the possible labs you can complete.

**Remember**

* You may receive at most 20 points worth of labs.
* Each lab is worth 2 points.
* They are due at **11pm on the day of your lab**.
* Each lab must have at least 3 commits.

**Marking**

* Labs get 2 if mostly correct, 1 if half-way there, 0 if wrong.
* If you get a zero, just submit more work in other categories.

## Lab Order

1. Week 1 (Sept 5-8) - Quiz 0 on Canvas
1. Week 2 (Sept 11-15) - `lab00-git`
1. Week 3 (Sept 18-22) - `lab01`
1. Week 4 (Sept 25-29) - `lab02` 
1. Week 5 (Oct 2-6) - `lab03`
1. Week 6 (Oct 9-13) - `lab04`
1. Week 7 (Oct 16-20) - `lab05`
1. Week 8 (Oct 23-27) - `lab06`
1. Week 9 (Oct 30-Nov 3) - `lab07`
1. Week 10 (Nov 6-10) - `lab08`
1. Week 11 (Nov 13-17) - No Labs (Midterm Break)
1. Week 12 (Nov 20-24) - `lab09`
1. Week 13 (Nov 27-Dec 1) - `lab10`
1. Week 14 (Dec 4-8) - No Labs

---

## Process

* First, you must `clone` this repo to your machine. You only need to do this 
once. The easiest way is with an RStudio Project. 
File > New Project > Version Control > Git. 
Then copy the url into the first field. 
You can save anywhere you like on your machine. 

* Now you're ready to go. So you want to start working...

* The below is the same as at [Stat-406/FAQ](https://ubc-stat.github.io/stat-406/faq/)

**If you are confused or concerned SAVE YOUR WORK and then post to Slack for help**

### Workflow in an RStudio Project

1. Make sure you are on `main` (Check the dropdown on the git tab.) 
Pull with the Blue Arrow ⬇️.
1. Create a new branch (name it anything you like).
1. Work on your documents and save frequently.
1. Stage your changes by clicking the check boxes.
1. Commit your changes by clicking **Commit**. 
1. Repeat 3-5 as necessary.
1. Push to GitHub with the Green Arrow ⬆️.
1. When done, go to GitHub and open a PR.
1. Use the dropdown menu to go back to `main` and avoid future headaches.

### Workflow from the command line

1. Make sure you are on `main`: `git branch -v`. If not on `main`: 
`git checkout main`.
1. Pull in any remote changes: `git pull`
1. Create a new branch `git branch -b <name-of-branch>`
1. Work on your documents and save frequently.
1. Stage your changes `git add <name-of-document1>` repeat for each changed 
document. `git add .` stages all changed documents. `git status` lists changed
documents.
1. Commit your changes `git commit -m "some message that is meaningful"` 
1. Repeat 3-5 as necessary.
1. Push to GitHub `git push`. It may suggest a longer form of this command, 
obey. 
1. When done, go to GitHub and open a PR.
1. Switch back to `main` to avoid future headaches. `git checkout main`.

