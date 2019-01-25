## Installing Jekylly on MacOS.

`$ brew install rbenv ruby-build`

**Add rbenv to bash so that it loads every time you open a terminal** 

```$ echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
$ source ~/.bash_profile
```
**Install Ruby**
```
$ rbenv install 2.5.0
$ rbenv global 2.5.0
$ ruby -v
$ gem install jekyll
```
