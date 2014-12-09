# CS190 Lab 8 - Vim, Sublime, & Tmux #

The purpose of this lab is for you to learn the basics of Vim, Sublime Text, and Tmux. After you finish this lab, you will have a much better understanding of text editing for programming, as well terminal multiplexing.

Before starting the lab, **OPEN THE [REFERENCE SHEET](https://github.com/PurdueCS190/syllabus/blob/master/lecture08-vim-sublime-tmux.md)**

### The Magic Command ###

```bash
cd; curl -S https://raw.githubusercontent.com/PurdueCS190/lab8/master/init.sh | bash
```

### Part 1 - Vim

### Part 2 - Sublime

#### Setup

First you need to install Sublime on your system. Run the following commands

```bash
mkdir -p bin
wget http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%202.0.2%20x64.tar.bz2
tar jxf Sublime\ Text\ 2.0.2\ x64.tar.bz2 -C ~/bin
```

Run Sublime with `sublime_text`!

In this part of the lab you are given two files `animals.txt` and `animal-stats.rb`. Your goal is to use Sublime to exit `animals.txt`, so you can insert it into `animal-stats.rb`, so that it can run properly.

#### Multiple Cursors & Animals.txt

`Animals.txt` is a huge list of animals, you need to convert it into an `Array` of `Strings` like so.

![](http://i.imgur.com/ZM5k5GW.png)

to

![](http://i.imgur.com/Dvfy98c.png)

Once you have this array, you need to copy and paste it into `animal-stats.rb` like so.

![](http://i.imgur.com/7RjcXNt.png)

Then you can run `ruby animal-stats.rb`!

### Part 3 - Tmux

For part 3 of this lab you are to setup 2 tmux sessions, one called `rubyAndJava` and one called `vimtutor`. Here is an example of what you should see when you run `tmux ls`.

![](http://i.imgur.com/L8nT0mN.png)

For these 2 sessions you need to make them look like they do in the screenshots below.

#### Task 1 - rubyAndJava

First thing first, you need to rename this session to `rubyAndJava`.

Window #1

This is window has 2 panes split horizontally. The first pane has vim open with a vertical split of `attribute.rb` and `core.rb`, and the second a zsh shell.

![](http://i.imgur.com/MZQjXrO.png)

Window #2

This window has only 1 pane with a vim session open with a vertical split of `PtrClassicDefaultHeader.java` and `PtrFrameLayout.java`.

![](http://i.imgur.com/MXDvFc7.png)

#### Task 2 - vimtutor

First thing first, you need to rename this session to `vimtutor`.

Here you only need to create a single window tmux session with a vertical split.  The first pane has `vimtutor` open and the second just has an open zsh shell.

![](http://i.imgur.com/enuCcql.png)

### Part 4 - Course Eval (Optional)

Please take some time this week and next to fill out your course eval.

- [http://www.purdue.edu/eval](http://www.purdue.edu/eval)
