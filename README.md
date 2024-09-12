# 리눅스 설정
Popos나 그외 리눅스를 쓸 때 필요한것들을 찾기 귀찮아서 복사할 목적으로 저장하는 repository

```sh
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.zsh/zsh-syntax-highlighting\necho "source ~/.zsh/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc\n
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions\necho "source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/.zsh/powerlevel10k
echo 'source ~/.zsh/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc

```

