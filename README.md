1. Install: stow, git
2. navigate to Home directory and clone this repo and rename it to `.dotfiles` 
3. to give permission to run the script: 
    
    ```bash
    chmod +x $HOME/.dotfiles/.bin/sync-dotfiles
    ```
    *verify permission*
    
    ```bash
    ls -l $HOME/.dotfiles/.bin/sync-dotfiles
    ```
4. download `zsh` and `oh-my-zsh`
5. make zsh default shell:
    ``` bash
        chsh -s $(which zsh)
    ```
6. also download these https://gist.github.com/n1snt/454b879b8f0b7995740ae04c5fb5b7df to complete the zsh
7. after running the script the files will populate and linked automatically
    
    ---

## structure 

in the home directory 

```bash
.dotfiles/
    ---- .bin
    ---- git
    ---- rest
```

