# Short Response Questions
## 1: If you are collaborating with a classmate what is the first thing that each of the team members needs to do? Why is it important to do this step? (Hint: After this step each member would have diverged from the main branch!)
If you are collaborating with a classmate, the *first thing* each of the team members needs to do is **make a new branch**. It is **important** to do this step because the work you do on here doesn't appear on the main branch beacuse you didn't merge the two branches. If you were to create a branch for fixing errors, you would make a branch so if you made a mistake the main branch would be unaffected.

## 2: Why do developers use branches?
Developers use branches because they can make edits, test new things, or fix bugs/errors without changing the main branch. Branches are also used to confirm with your teammates (If you **are** working with one) if the changes are good.

## 3: What is git? What is github? How does git and github work together?
Git is a distributed **Version Control System**, or simply a *control system* that allows you to track the history of your code, and make changes to your code. Github is a company that offers Git repository on its website, [github.com](github.com). Github also stores repositories where the code is stored, and allows for collaboration between developers. Github is the host for Git, and you can use Git for free by going on the website offered by the company.

## 4: What is wrong with the following command sequence? What should be the *correct* command sequence?
```python
git commit -m "saving work"
git add .
git push
```

This command sequence is wrong because you put the commit before you did `git add . `. The correct command sequence is shown below:

```python
git add .
git commit -m "saving work"
git push
