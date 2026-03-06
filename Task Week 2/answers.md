# Answers

1. Create a schedule of your faculty lectures using markdown tables.
   |Periods|   SAT  |  SUN  |  MON   | TUES | WEDN |  THU  |
   |:-----:|:------:|:-----:|:------:|------|:----:|-------|
   |  1st  |   CS   |  OOP  |        |      |  IS  |       |
   |  2nd  |        | Logic |        |      |      |       |
   |  3rd  |   IT   |       |Calculas|      |      |       |
   |  4th  |        |       |        |      |      |       |
   |  5th  |        |       |        |      |      |       |

   
2. Write the git commands needed for each of the following scenarios:
    - You want to add all modified files to git staging without specifying each one of them.
      -  `git add .`
    - You have a local repository and you need to add a remote with name `deploy` and url `https://git.heroku.com/example-app.git`.
      -   `git remote add deploy https://git.heroku.com/example-app.git`
    - You want to get the history of commits in the repository where each commit is represented by one line.
      -  `git log --oneline`
    - You try to make a commit but git asks you to enter your name and email first.
      -  `git config --global user.name "MohamedYounis"` & `git config --global user.email "myemail@gmail.com"`
    - Your work is present on the branch feature/chat and you want to merge it with the branch development.
      -  `git checkout development` then `git merge feature/chat`
    - You realize that you want to add one more file to the last commit without creating a new commit.
      -  `git add <filename>` then `git commit --amend --no-edit`

3. What does the HEAD keyword refer to in git?
   - It is the reference to the most recent commit in current branch.

4. What are the problems with this commit message? list all what you notice.
   - Commit message is general.
   - There is no related files.
   - There is no balnk lines.
   - Body is not presented in bullet points.
   - The Body follows the present continuous tense, not the infinitive form of the verbs.
   - There is no issue tracker.

5. Which of these statements in NOT correct? and why?
  - Git is a cloud-based service to store remote repositories.
    - Because Git is a software that we install and run it locally.