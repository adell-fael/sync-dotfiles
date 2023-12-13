
- run this to give permission to run the script  

```bash
chmod +x $HOME/.dotfiles/.bin/sync-dotfiles
```

- verify permission

```bash
ls -l $HOME/.dotfiles/.bin/sync-dotfiles
```

also the structrue is like this 

---
## structure 

```bash
.dotfiles/
    ---- .bin
    ---- git
    ---- rest
```

---

## note

to restore them on a new device 

steps

```bash
cd ~/.dotfiles
```


### stow each one like to resore (automate this later)

```bash
stow git
```