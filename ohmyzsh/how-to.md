# What is Oh My Zsh?

**Oh My Zsh** is an open source, community-driven framework for managing the Z shell (Zsh). It is a powerful collection of plugins and themes that can enhance the default Zsh experience and make it more user-friendly and customizable.

**Oh My Zsh** is a popular choice among developers, system administrators, and power users who want to improve their command-line experience and productivity by leveraging the power of the Zsh shell along with a rich ecosystem of plugins and themes.

Website: https://ohmyz.sh/

# Step 1: Downloading Oh My Zsh

Easiest way to install is via `curl` by copying and pasting the below command. Make sure you're in your system's root folder.
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
# Step 2: Configuring the `.zshrc` file

The `.zshrc` file contains the script that is run when you start a new zsh shell (`rc` stands for "run commands"). So if you make changes to this file you have to start a new shell to see them take effect.

You can customise your terminal by running `open ~/.zshrc` to open the `.zshrc` file in your system's root folder (the `~` tilde symbol means home directory).

Note: if you're on macOS Catalina or above you may get the error `zsh: permission denied:` - you will need to configure permissions to open the file with `chmod +x ~/.zshrc`.

# Step 3: Changing the Terminal theme

Choose your theme from the [Oh My Zsh Themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes) and change the `ZSH_THEME=""` line in the `.zshrc` file.

For example, if you use the 'agnoster theme' configure the line to this `ZSH_THEME="agnoster"` in the `.zshrc` file.
