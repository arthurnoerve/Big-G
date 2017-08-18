# Big-G
For those of us who regularily push and pull to a git repository while developing, typing all of it gets quite old, fast:

```bash
git add -A
git commit -m "Stuff..."
git push
git pull
```

To solve this, we made Big G. It currently takes one argument and is therfore very easy to use.

## Usage
To do all the git stuff in one go and use "Fix" as the commit message just type G.

```bash
G 
```
If you need your own message, type it in as the first and only argument to G.

```bash
G "Commit message here"
```



## Further development
* Implement an auto commit message that is more descriptive than just "Fix". Maybe find out what you have been doing. Anything is better than fix.
* Implement proper error handlig and git edit flow.
* Add optional flag for voice message on complete
* fs