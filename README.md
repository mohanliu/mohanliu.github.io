## Installing Jekylly on MacOS.

`$ brew install rbenv ruby-build`

**Add rbenv to bash so that it loads every time you open a terminal** 

```
$ echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
$ source ~/.bash_profile
```
**Install Ruby**
```
$ rbenv install 2.5.0
$ rbenv global 2.5.0
$ ruby -v
$ gem install jekyll
```
**Further steps following Github Page instructions**

Check page: [Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)

**Run local jekyll server**:

`$ bundle exec jekyll serve`

## Create website
[Create website from Scratch](https://medium.com/@robcobbable/make-a-resume-website-from-scratch-991845147ec)
