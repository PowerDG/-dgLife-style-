### cmder.net

Portable console emulator for Windows



Cmder is a software package created out of pure frustration over the absence of nice console emulators on                  

  Windows. It is based on amazing software, and spiced up with the Monokai color scheme and a custom prompt                    layout, looking sexy from the start.                

#### With help of the best

Think about cmder more as a software package than a separate app. All the magic is happening through                            [ConEmu](https://conemu.github.io). With enhancements from                            [Clink](https://mridgers.github.io/clink/).                        

​                            ![Personally, I hate the absence of padding](https://cmder.net/img/bye_thumb.png)                        

#### Total portability

Carry it with you on a USB stick or in the Cloud, so your settings, aliases and history can go anywhere                            you go. You will not see that ugly Windows prompt ever again.

​                            ![Look at all these neat binaries included.](https://cmder.net/img/git_thumb.png)                        

#### Git and others

Oooh yes! If you decide to use the                            *slightly* bigger                            [                                 git-for-windows](https://gitforwindows.org/) version, you will have all Unix commands ready in PATH so that you can                            `git init` or                            `cat` instantly on every machine.                        





#### Installation

1. Unzip
2. (optional) Place your own executable files into the                            `bin` folder to be injected into your PATH.
3. Run                            **Cmder**                            *(Cmder.exe)*                        

### Keyboard shortcuts

#### Tab manipulation

- ​                                `Ctrl + `` :                                **Global** Summon from taskbar

- ​                                `Win + Alt + p` : Preferences (Or right click on title bar)

- ​                                `Ctrl + t` : New tab dialog (maybe you want to open cmd as admin?)

- ​                                `Ctrl + w` : Close tab

- ```
  Shift + Alt + number
  ```

   : Fast new tab:                                

  1. ​                                        `1.` CMD
  2. ​                                        `2.` PowerShell

- ​                                `Alt + Enter` : Fullscreen

#### Shell

- ​                                `Ctrl + Alt + u` : Traverse up in directory structure (lovely feature!)
- ​                                `End, Home, Ctrl` : Traverse text as usual on Windows
- ​                                `Ctrl + r` : History search
- ​                                `Shift + mouse` : Select and copy text from buffer
- ​                                `Right click / Ctrl + Shift + v` : Paste text 

### Notes / Docs

#### Aliases

There is simple support for aliases. They can be created by using the                            `alias` command like this:                            `alias ls=ls --color $*`. They are pretty much just                            *doskeys* in                            `/config/aliases`. One per line. And make sure to handle arguments by putting argument variables                            `$*` somewhere.

#### Updating + Building

There is not much going on here. But if you want to get most recent updates for Conemu just tick                            *auto-updating* in preferences. If you want to clone the repo and build it yourself, you will                            need                            *PowerShell >=3.0 and 7z*. When you are set on that, just run                            `scripts/build.ps1`.

#### Documentations

Most of the Cmder functionality are documented in the                            [readme](https://github.com/cmderdev/cmder/blob/master/README.md) file on GitHub.                            We have extented help available in [Cmder Wiki](https://github.com/cmderdev/cmder/wiki), also regarding integration.                        

​                            If you're having trouble with anything, please have a look at the GitHub                            [issues](https://github.com/cmderdev/cmder/issues?q=is:issue), or create                            [a new one](https://github.com/cmderdev/cmder/issues/new). 
​                            We'll be happy to help, but you might have a better chance to find                            solutions on the pages of the upstream projects. Those are:

- Console emulator ~                                [Conemu](https://conemu.github.io/)                            
- Cmd.exe enhancements ~                                [clink](https://mridgers.github.io/clink/)                            
- Unix tools on windows ~                                [git for windows](https://gitforwindows.org/)                            

​        Created by        [Samuel Vasko](https://github.com/samvasko)