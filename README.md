# testing commit emails

To create a new commit:

```fish
date > last-updated; git add last-updated; git commit -m "change number "(git log --oneline | wc -l | tr -d ' '); git push
```
