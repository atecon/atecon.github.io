# Some stuff from myself
To be written


# References for working with github-pages and jekyll
- https://youtu.be/EmSrQCDsMv4
- https://ejayledesma.github.io/blog/2019/08/12/building-my-website-using-GitHub-Pages-and-Jekyll/


# Installation of jekyll under ubuntu

```
# Install jekyll
sudo apt-get install ruby-full build-essential zlib1g-dev
gem install jekyll bundler

# update .bashrc
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

# Enter repo of interest and...
gem install jekyll bundler
jekyll new . --force
```
