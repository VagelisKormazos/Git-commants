# Git-commants

1. git pull origin master
--------------------
2. Checkout the Branch: First, ensure you are on the branch where you want to stash changes.
 You can use the git checkout Vagelis command to switch to the "Vagelis" branch.

bash:
git checkout Vagelis

3.Stash Changes: Once you're on the correct branch, you can use the git stash command to
 stash your changes.

bash:
git stash

4.Verify Stash: You can verify that the changes have been stashed by running git stash list
This command will list all stashed changes.

bash:
git stash list

5.git branch: Αυτή η εντολή σας επιτρέπει να δείτε όλα τα branches στο repository σας.
Χρησιμοποιήστε το git branch για να δείτε τα branches και το git branch -a για να δείτε 
και τα απομακρυσμένα branches.

bash:
git branch

6.git checkout: Αυτή η εντολή σας επιτρέπει να μετακινηθείτε ανάμεσα σε διαφορετικά branches.
 Μπορείτε να χρησιμοποιήσετε το git checkout <branch-name> για να μετακινηθείτε σε ένα άλλο
 branch.
7.git merge: Αυτή η εντολή χρησιμοποιείται για να συγχωνεύσετε ένα branch με ένα άλλο. 
Χρησιμοποιήστε το git merge <branch-name> για να συγχωνεύσετε το branch <branch-name> με 
τον τρέχοντα branch.

8.git rebase: Αυτή η εντολή επιτρέπει την αναδιάταξη των commits σας πάνω σε ένα άλλο 
branch ή στην κορυφή ενός branch. Χρησιμοποιήστε το git rebase <branch-name> για να
 αναδιατάξετε τα commits σας επάνω στο branch <branch-name>.

9.git reset: Αυτή η εντολή χρησιμοποιείται για να επαναφέρετε την κατάσταση του
 repository σας σε ένα συγκεκριμένο commit. Μπορείτε να χρησιμοποιήσετε το git 
reset <commit> για να επαναφέρετε το repository σας στο commit <commit>.

10,git log: Αυτή η εντολή σας επιτρέπει να δείτε το ιστορικό των commits στο
 repository σας. Χρησιμοποιήστε το git log για να δείτε τη λίστα των commits.
