# Install prerequirements

```sh
sudo dpkg --configure -a
```

```sh
echo '# Install Ruby Gems to ~/gems' >> ~/.zshrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.zshrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

```sh
gem install jekyll bundler
```
