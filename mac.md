## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control software responsible for tracking changes in a project or file.

2. What is the difference between Git and GitHub?
it is software used in a CLI, it doesn't have a GUI. Github is a website that hosts git projects, github just makes it easier for people to visualize and collaborate on projects.

3. Why do we create a branch? 
We create branches to isolate the work from the main branch so as to not disrupt the work and introduce bad code before it gets vetted by a senior software engineer.

4. What is the purpose of a Pull Request?
To show others changes you've made to your branch, that way someone up the chain can review the code and merge if the code is good.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
The "git checkout" command can be used to switch between branches

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git merge, merges forked work with each other; any changes made on either get saved onto one branch. Git fetch downloads a repo but leaves your work unaffected. git pull downloads repos but will execute git merge, which leaves your work merged with the downloaded repo. 

7. What is a merge conflict?
A merge conflict is what happens when multiple commits are changing the same thing.

8. How do you resolve a merge conflict?
By manually editing the file in question and selecting the changes that get to make the merge. 