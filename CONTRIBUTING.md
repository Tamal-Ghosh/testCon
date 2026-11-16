# Practice workflow

Use a separate branch to try a small change:

```sh
git switch -c practice/update-text
```

Edit a text file, then review and commit your change:

```sh
git diff
git add hello.txt
git commit -m "Update practice text"
git push -u origin practice/update-text
```

Open a pull request on GitHub to review the branch before merging it.
