# VIM for RAILS

### What is this?

It's an entire VIM 'distro' in one file including all the bundles I use for Ruby on Rails work.

### Why?

I used to use TextMate, which was great, but then I moved to Sublime which was
awesome, and then I heard about VIM. At first, I thought anyone using VIM was
crazy, but after reading more and more about it, I think if you're programming long enough, you'll eventually switch
to VIM (or eMacs). So why not switch sooner rather than later. You do plan on being a programmer for a long time, no?

Unfortunately, setting up VIM for Rails is a pain in the a$$S! Even with other solutions, you are dealing with cloning, submodules, etc. Yuck. Plus all the research to find the bundles you need to become productive. Annoying. You have real work to do.

So I created this, so anyone new could quickly get up and running with VIM (with one file, read below).

Disclaimer: I've done very little work except for setting up this repo. I did not create any of the wonderful plugins, VAM, or anything else related. I simply did a lot of research to find all the best plugins that work for me using Rails. 

### How?

1. Fork this repo

    You will want to customize things for yourself, trust me. Fork it.
    You may also want to fork my snippets fork in order to customize them for your use. If you do, you will want to change the github username in the vimrc to reflect that change.

2. Run
```
ruby activate.rb
```

    Or create the symlinks yourself but I'm lazy.
    Be warned: This will overwrite any existing .vimrc, .gvimrc or .vim/ files you have in your home directory. (I did not write activate.rb either, but I am good at copy/paste. :) )


3. Install dependencies, like git and hg needed by VAM (vim-addons-manager). You will also need syntax checkers installed if you want to use that feature. For example: jslint for javascript.

    Homebrew is your friend with Mac. 
    ```
    brew install git
    brew install hg
    ```
    Use Aptitude with Linux (at least ubuntu-based distros)
    ```
    sudo aptitude install git-core
    sudo aptitude install mercurial
    ```

4. Run 
```
vim
```


VAM will download and setup VIM for all addons. 

Let me repeat that. 

VAM will download and setup VIM for all addons!

No cloning, no submodules to manage. Nothing. Everything in one file!

Warning: You may have to run the vim command multiple times for it to work properly. 
If you get stuck, press arrow-up. Weird. I don't know why. I have had better luck using 
terminal VIM for the initial setup and then once everything is set up switching to 
MacVIM if you prefer to use the mouse. 

Good luck, and remember this is a work in progress since I am also new to VIM.
