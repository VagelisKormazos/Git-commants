
# Git Commands Cheat Sheet

Αυτό το αρχείο περιέχει μια λίστα από βασικές εντολές Git που είναι χρήσιμες κατά την διάρκεια της ανάπτυξης λογισμικού.

## Οδηγίες για το Χρήστη

1. **Git Pull:** Ανακτάει τις αλλαγές από το remote repository και συγχωνεύει με τον τρέχοντα local branch.

    ```bash
    git pull origin master
    ```

2. **Checkout the Branch:** Βεβαιωθείτε ότι βρίσκεστε στο branch όπου θέλετε να κρατήσετε τις αλλαγές σας.

    ```bash
    git checkout Vagelis
    ```

3. **Stash Changes:** Κρύψτε τις τροποποιήσεις σας στο τρέχον branch.

    ```bash
    git stash
    ```

4. **Verify Stash:** Επιβεβαιώστε ότι οι τροποποιήσεις σας έχουν αποθηκευτεί επιτυχώς.

    ```bash
    git stash list
    ```

5. **Git Branch:** Προβολή όλων των branches στο repository, συμπεριλαμβανομένων και των απομακρυσμένων branches.

    ```bash
    git branch        # Προβολή όλων των local branches
    git branch -a     # Προβολή όλων των local και remote branches
    ```

6. **Git Checkout:** Μετακινηθείτε ανάμεσα σε διαφορετικά branches.

    ```bash
    git checkout my-branch    # Μετακίνηση στο branch με όνομα "my-branch"
    ```

7. **Git Merge:** Συγχωνεύστε ένα branch με ένα άλλο.

    ```bash
    git merge feature-branch    # Συγχώνευση του branch "feature-branch" με τον τρέχοντα branch
    ```

8. **Git Rebase:** Αναδιάταξη των commits σας πάνω σε ένα άλλο branch ή στην κορυφή ενός branch.

    ```bash
    git rebase main    # Αναδιάταξη των commits πάνω στο branch "main"
    ```

9. **Git Reset:** Επαναφέρετε την κατάσταση του repository σας σε ένα συγκεκριμένο commit.

    ```bash
    git reset HEAD~3    # Επαναφορά του repository σας τρία commits πριν από το τρέχον commit
    ```

10. **Git Log:** Δείτε το ιστορικό των commits στο repository σας.

    ```bash
    git log    # Προβολή του ιστορικού commits
    ```
