# Command Line Wizardy

## Using the fzf Command
We talk about and use the command fzf. It is not on thomas and not on a lot of machines by default. If you are running a Linux system you can run 
```
curl -o fzf http://blue.butler.edu/~tmwiegan/fzf
```
If you are planning on using fzf on a different OS, their documentation is here: https://github.com/junegunn/fzf

#### Search syntax

Unless otherwise specified, fzf starts in "extended-search mode" where you can
type in multiple search terms delimited by spaces. e.g. `^music .mp3$ sbtrkt
!fire`

| Token     | Match type                 | Description                          |
| --------- | -------------------------- | ------------------------------------ |
| `sbtrkt`  | fuzzy-match                | Items that match `sbtrkt`            |
| `'wild`   | exact-match (quoted)       | Items that include `wild`            |
| `^music`  | prefix-exact-match         | Items that start with `music`        |
| `.mp3$`   | suffix-exact-match         | Items that end with `.mp3`           |
| `!fire`   | inverse-exact-match        | Items that do not include `fire`     |
| `!^music` | inverse-prefix-exact-match | Items that do not start with `music` |
| `!.mp3$`  | inverse-suffix-exact-match | Items that do not end with `.mp3`    |


## YouTube Link
https://youtu.be/gAZV_a_bb0Y


## Challenges

### Make The Cheatsheet version of the fzf MAN thingy

### Make a script to bring up fzf and ask you want template file you want

### Play around with your prompt make it dope as hell

### Use vim, it's a really powerful tool and vimtutor will help you out. 
