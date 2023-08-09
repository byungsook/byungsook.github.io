# Install

install wsl2

`wsl --install`

launch wsl, install ruby

```bash
sudo apt update
sudo apt install git curl autoconf bison build-essential \
    libssl-dev libyaml-dev libreadline6-dev zlib1g-dev \
    libncurses5-dev libffi-dev libgdbm6 libgdbm-dev libdb-dev \
    imagemagick
```

https://github.com/rbenv/rbenv#basic-git-checkout

```
rbenv install 2.7.5
gem install bundler

cd `repo`
git checkout main

bundle install
```

to run,

```
cd /mnt/c/dev/byungsook.github.io
bundle exec jekyll serve --lsi
```