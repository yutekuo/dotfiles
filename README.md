# dotfiles

This repository automates the setup of essential development tools and configuration on macOS, including:

- Homebrew
- Oh My Zsh
- Powerlevel10k theme
- NVM (Node Version Manager)
- Git aliases
- Custom `.zshrc`, `.gitconfig`, and more

## 📦 Installation Checklist

- [ ] Install[Homebrew](https://brew.sh/)
- [ ] Install [Oh My Zsh](https://ohmyz.sh/)
- [ ] Install [Powerlevel10k Theme](https://github.com/romkatv/powerlevel10k)
- [ ] Install [NVM (Node Version Manager)](https://github.com/nvm-sh/nvm)
- [ ] Initialize Git:
  - Set username:
    ```
    git config --global user.name "FIRST_NAME LAST_NAME"
    ```
  - Set user email:
    ```
    git config --global user.email "MY_NAME@example.com"
    ```
  - Customize color config:
    ```
    git config --global color.branch.upstream "yellow bold"
    ```
- [ ] Clone the repository and place it under the root directory:

  ```
  git clone https://github.com/yutekuo/dotfiles.git ~/.dotfiles
  ```

- [ ] Add the following lines to the `~/.zshrc` file

  ```
  source $HOME/.dotfiles/.git_aliases
  source $HOME/.dotfiles/.zshrc_aliases
  ```
