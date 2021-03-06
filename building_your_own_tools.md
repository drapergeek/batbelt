build-lists: true
# Building Your Own Bat-Belt

### Jason Draper
### @drapergeek
### thoughtbot

---

# Who am I?

* Developer @ thoughtbot
* Husband/Father
* General Geek
* Avid wakeboarder

---
![left filtered](vertical_default.eps)

# What's a thoughtbot?

* Build fun stuff for clients
* Apprentice program
* Upcase
* Open Source
* Investment time

---
# What are dotfiles?

* Really? They're just hidden files
* In our case - they're configuration files
* They are what makes each developer's setup unique

---
# Cool, can you be a bit more specific?

* shell configuration
* text editors
* Git

---

# Shell stuff
## Prompts

![inline](prompts/default.jpg)

---
# Shell stuff
## Custom Prompts

![inline](prompts/bit_of_color.png)
![inline](prompts/airline.png)

---

# Shell stuff
## Custom Prompts

![inline](prompts/previous_command_status.png)
![inline](prompts/shortened.png)

---

# Shell stuff
## Custom Prompts

![inline](prompts/dots.png)

---
# Shell stuff
## History
* change your history length
* set your history to go across multiple terminals

---
# Shell stuff

* Set ENV information - your name and/or email

```bash
export NAME='Jason Draper'
export EMAIL='jason@drapergeek.com'
```
---

# Git
* Set your name and email!
* Set preferences on merging and pushing branches
* Add quick commands for common things

---

# Git commands

```bash
git rc # git rebase --continue
git dm # git diff master
git done # merge the to master and push to origin
git uf # git reset --hard HEAD
```

---

# Aliases

## Type less, do more!

```bash
alias short='long'
```

---
# Aliases

```bash
$ d # cd ~/dotfiles
$ c # cd ~/code
$ g # git
$ gi # gem install
$ s # rspec
$ fs # foreman start
$ m # migrate
$ rs # rails server
$ rc # rails console
```

---

# Vim

## Make common things easier

```vim
map <silent> <F5> mmgg=G'm "Fix entire file indentation
nnoremap <leader><leader> <c-^> "Switch between the last two files
```

## Encourage good habits

```vim
map <Leader>v :vsp ~/.vimrc<CR> "Open my vim config
map <Leader>s :vsp ~/.aliases<CR> "Open my aliases file
```

---

# Why does this matter?

* Efficiency!
* Can help you learn
* Simplify your life

---

## Why does this REALLY matter?

* It's an extension of your craft
* Take pride in your job, take pride in your tools
* Continuously improve your process
* Let's not kid ourselves - it's awesome

---
# How do I start?

* Find a base set of dotfiles
  * http://github.com/thoughtbot/dotfiles
  * https://dotfiles.github.io/
  * https://github.com/holman/dotfiles
* Fork it!
* Start a daily list of things you'd like to customize
* Spend 30 minutes, 1 morning a week adding them

---

# Thanks!

## Questions?
