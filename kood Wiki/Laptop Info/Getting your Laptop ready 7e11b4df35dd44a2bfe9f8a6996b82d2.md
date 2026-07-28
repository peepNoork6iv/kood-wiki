# Getting your Laptop ready

Updated: May 20, 2026 10:23 AM

Here you can get short instructions and links on how to get your laptop prepared. If you need help after trying to set up everything, then our team can assist you during the very first day. Also, a good way is to ask about your problems on Discord!

**Instruction video for Windows:**

[https://youtu.be/bfgq8D_L9vk](https://youtu.be/bfgq8D_L9vk)

[MacOS](Getting%20your%20Laptop%20ready%207e11b4df35dd44a2bfe9f8a6996b82d2.md)

[Windows](Getting%20your%20Laptop%20ready%207e11b4df35dd44a2bfe9f8a6996b82d2.md)

[Linux](Getting%20your%20Laptop%20ready%207e11b4df35dd44a2bfe9f8a6996b82d2.md)

# Mac OS

First of all, install the **Homebrew ([https://brew.sh](https://brew.sh/))**

After that, using Homebrew - install these utils 

```bash
**brew install coreutils
brew install jq
brew install git (if you don’t have xCode)
brew install golang (or install it from [https://golang.org/dl/](https://golang.org/dl/))
brew install gofumpt**
```

Run the `brew list` command to be sure that you have all the necessary packages

**Visual Studio Code ([https://code.visualstudio.com](https://code.visualstudio.com/))**

**Terminal commands after you have cloned your repo at the start of the sprint**

```bash
echo .DS_Store >> .gitignore
git commit -am “remove .DS_Store files”
touch ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
echo .DS_Store >> ~/.gitignore_global
```

# Windows

**How to Enable the Linux Bash Shell in Windows 10: [https://www.laptopmag.com/articles/use-bash-shell-windows-10](https://www.laptopmag.com/articles/use-bash-shell-windows-10) (NB! Only steps 1 to 9 are required. No need to install the bash!)**

**Ubuntu installation ([https://ubuntu.com/wsl](https://ubuntu.com/wsl)) - Ubuntu terminal for Windows 10**

***In case if have** **Windows 7, then here is Linux distribution for  ([http://www.cygwin.com/](http://www.cygwin.com/))***

**Install the Homebrew ([https://brew.sh](https://brew.sh/)) in Ubuntu Terminal. Please read the instructions on the brew.sh page carefully, then proceed to install these packages:**

```bash
**brew install coreutils
brew install jq
brew install git
brew install golang
brew install gofumpt**
export PATH=$PATH:/usr/local/go/bin
```

**Visual Studio Code ([https://code.visualstudio.com](https://code.visualstudio.com/)) - Windows and agree with all points in installation**

- **Remote Development Extention ([https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)**
    - **More information about WSL extension** ([https://code.visualstudio.com/docs/remote/wsl](https://code.visualstudio.com/docs/remote/wsl))

> Make sure to install the WSL 2 version
> 

After downloading the WSL extension, then click the green "**Open a Remote Window**" button

![](Getting%20your%20Laptop%20ready/wsl1.png)

And in the menu click on the "**New WSL Window**"

![](Getting%20your%20Laptop%20ready/wsl2.png)

When the WSL window is loaded just run the command `brew list` and it should print out all downloaded packages

# Linux

**Linux**

**Homebrew ([https://brew.sh](https://brew.sh/)) (just paste the command found on the mane page in your terminal**

```bash
brew install coreutils
brew install jq
brew install git
brew install golang
brew install gofumpt
```

**Visual Studio Code ([https://code.visualstudio.com](https://code.visualstudio.com/))**

- Open the **Command Palette** via **(Ctrl+Shift+P)** and type shell command to find the Shell Command -> install ‘code’ command in PATH

Run the `brew list` command to be sure that you have all necessary packages

# /kood Jõhvi Laptops

All /kood Jõhvi laptops are with preinstalled **Mint 21.1**. Password is: **kood**