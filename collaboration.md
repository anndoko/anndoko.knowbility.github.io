# Team Wonder Squad - OpenAir Competition (Website Redesign & Development for Fashionable Adoptions)


# IMPORTANT: TEAM COLLABORATION
- Add **comments** so that others can read your code more easily

- Be sure to **commit your change** every now and then so that others can track changes/debug more easily

    **How to commit your change**

    1. Add the file(s) you have modified to the staging area using:

      ```
      $ git add .
      ```

      ```
      $ git add <filename>
      ```
      (Use `$ git reset` to undo `$ git add .`)

    2. Commit and write what changes you have made in the commit message using:
      ```
      $ commit -m "<YOUR NAME>: <TASK>"

      e.g. commit -m "Anndo: add css code to style the buttons"
      ```


- **Make a new branch to work on each of your tasks**, and then push it to GitHub and create a **pull request** once you have it done. The purpose of using branches is to avoid messing up with the master branch.

    **How to use branch to collaborate**

    1. Update your master branch using:

      ```
      $ git pull origin master
      ```

    2. Create a new branch using:

      ```
      $ git branch <TASK NAME>

      e.g. git branch homepage-responsiveness
      ```

    3. Switch to the branch you just created using:

      ```
      $ git checkout <BRANCH NAME>

      e.g. git checkout homepage-responsiveness
      ```

    4. After you complete the task, switch to your master branch using:

       ```
       $ git checkout master
       ```

    5. Push your branch using:

       ```
       $ git push origin <BRANCH NAME>
       ```

    6. Go to GitHub and create a pull request. Wait for the tech lead to review and merge the branch to master.
