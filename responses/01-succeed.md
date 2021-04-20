Good job!

You may notice that there is a automated Github Workflow down at the bottom of
this page. This workflow does nothing for now. Yet, it is recommended to enable
continuous integration test before you merge your changes to the `main` branch.

You may enable the branch protection to avoid merging untested code into `main`
branch `after the unit test is done`:

1. Click the `Settings` tab on your Github repository page
2. Click `Branches` from the menu
3. Click button `Add rule`
4. Type in `main` in text box `Branch name pattern`
5. Check box `Require status checks to pass before merging`, and then boxes
   `Require status checks to pass before merging` and `linux-test`
6. Cehck box `Include administrators` to force rule to all users
7. Click button `Create` to apply the rule
8. Try to edit any file on the `main` branch online, and you will see
   `You can’t commit to main because it is a protected branch.` on the bottom.
   Do `NOT` save the changes!

Once you finished the steps above, make a comment to continue!
