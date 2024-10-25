## INSTALLATION (MAC OS)
- [Clone this repository](https://github.com/0xDVC/nvim4j-config)

- Ensure lua is installed. 
```bash    
   brew install lua
```

- Install Neovim.
```bash
   brew install neovim
```

- Open directory of cloned repository and find its contents.
```bash
--|  init.lua
  |  lazy-lock.json
  |__ lua /
      |__ config /
          |__ ...
      |__ plugins /
          |__ ...
```

- Copy contents to ```~/.config/nvim```.
```bash
    cp -r nvim4j-config/* ~/.config/nvim
```

- Now open any desired directory, and open neovim with or without specifying any file to edit.
```bash
    nvim 
```

- Lazy automatically installs the plugins upon launch. Kindly wait till installation is through. Enjoy🙂


**[Credits to UnknownKoder](https://www.youtube.com/watch?v=zbpF3te0M3g&t=365s)

