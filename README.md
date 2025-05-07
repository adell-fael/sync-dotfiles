1. Install: stow, git
2. navigate to Home directory and create `.dotfiles` and clone this repo/setup inside it
3. - run this to give permission to run the script  
    
    ```bash
    chmod +x $HOME/.dotfiles/.bin/sync-dotfiles
    ```
    
    - verify permission
    
    ```bash
    ls -l $HOME/.dotfiles/.bin/sync-dotfiles
    ```
4. after running the script the files will populate and linked automatically
    
    ---

## structure 

in the home directory 

```bash
.dotfiles/
    ---- .bin
    ---- git
    ---- rest
```

