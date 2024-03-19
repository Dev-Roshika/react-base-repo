## Cloning a Single Branch from a Git Repository

To clone a single branch from a remote Git repository, you can use the `git clone` command with the `-b` (branch) and `--single-branch` options. Here's the command syntax:

```
git clone -b <branchname> --single-branch <remote-repo-url> [<local-directory>]
```
- `<branchname>`:  Name of the branch you want to clone.
- `<remote-repo-url>`:  URL of the remote repository.
- `[<local-directory>]`: Optional local directory where you want to clone the repository. If not specified, the repository will be cloned into a directory with the same name as the repository.

### Example
Let's illustrate how to clone the branch react-mini from a repository ```https://github.com/Dev-Roshika/react-base-repo.git```

1. Create a Project Folder:  Create a folder where you want to clone the repository.

2. Clone the Branch:  Open the terminal and navigate to the project folder.
3. Then, execute the following command:
   ```
   git clone -b react-mini --single-branch https://github.com/Dev-Roshika/react-base-repo.git .
   ```

This command clones the `react-mini` branch from the specified repository into the current directory (`.`).

After executing the command, the project will be cloned into the specified directory, containing only the commit history and files relevant to the react-mini branch.
