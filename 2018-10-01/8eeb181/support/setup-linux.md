## Setup for linux

```sh
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install cmake

$ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
$ \curl -sSL https://get.rvm.io | bash
$ source ~/.rvm/scripts/rvm

# fork and clone your fork of blog website and change dir to it
$ git clone https://github.com/<username>/blog.jboss-outreach.org.git
$ cd blog.jboss-outreach.org

$ rvm install "ruby-2.4.2"
$ rvm use "ruby-2.4.2"
$ gem install bundler
$ bundle install
$ bundle exec jekyll serve --host 0.0.0.0
```