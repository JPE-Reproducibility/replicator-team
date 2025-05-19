# 🌐 JPE Replicator Website

Welcome to your replicator assigment! Each replicator will contribute a JSON file describing themselves.
These files are collected and displayed on the website automatically.

## 🧑‍💻 Your Task

1. **Fork** this repository.
2. **Clone** your fork locally.
3. Create a new branch with your initials, and a name that describes the task you are completing. I would say `git branch fo/add_user`.
4. In the `_data/` directory, create a new file named **yourusername.json**, where `yourusername` is your github user name. Please change the entries for each of the keys below, choosing something appropriate:
    ```json
    {
      "emoji": "😄",
      "introduction": "Hi, I'm learning Git!",
      "computing": "Python, a bit of R",
      "institution": "University of Example"
    }
    ```
5. **Commit and push** your change:
    ```bash
    git add _data/yourusername.json  #change yourusername
    git commit -m "Add my intro data"
    git push origin fo/add_user
    ```
    this last command pushes the local branch `fo/add_user` to my fork on github.com. from there I can now...
6. **Create a Pull Request** to this repository.

Once merged, your profile will appear on the website!
